---
title: Computational Plenoptic Imaging
date: 2018-12-04 16:23:40
tags: Computational Plenoptic Imaging
categories: paper reading
copyright:
updated:
---

This is the review of the field of "computatational plenoptic imaging", the paper can be accessed by [click here](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-8659.2011.02073.x) .

# Abstract #
- The plenoptic function is a ray-based model for lights which includes the color spectrum(色谱)+spatial+temporal+directional variation.
- In the process of the transaction from photons into electrons, all visual information will be lost irreversibly BY *CCD* and *CMOS* sensors.
- The paper mainly focused on " optically encode the dimensions of the plenoptic function transcending those captured by traditional photography and reconstruct the recorded information  computationally."

# Introduction #
- Single human eye can perceive a two-dimensional trichromatic image(二维三色图像).
- Computational processing and optical fabrication, image processing begin to transcend limitation because of natural diversity of perceptual system and digital camera tech. 
- By capturing highly detailed visual information, geometry、scene  reflectance、 materials and refractive index properties can be acquired essentially.
- We use single-device and multi-shot approaches to capture plenoptic properties of static scenes.
- Multiple devices are the most expensive one, it will reduce spatial resolution of captured content in favour of increased plenoptic resolution.
- Using different properties of variety of scenes and hardware is the most efficient way.

## Computational photography and plenoptic imaging ##
-  Plenoptic imaging considers a subset of computational photography approaches; specifically,
those that aim at acquiring the dimensions of the plenoptic
function with combined optical light modulation and computational reconstruction. 

## Overview and definition of scope ##
- *The report mainly tells as "the state of the art in joint optical light modulation and computational reconstruction approaches for acquiring the dimensions of the plenoptic function"*
- The frame of the paper will be 
> Acquisition of HDR 

> The color spectrum

> Light field and directional variation

> Spatial super-resolution and focal surface

> High-speed events

> Acquisition of light properties

# High Dynamic Range Imaging #
- The dynamic range of an imaging system is defined as the ratio of largest and smallest possible value in the range of a recorded signal, as opposed to the domain.
- Standard sensors have a limited dynamic range.
- The paper focus on telling ***the acquisition of HDR imagery***.

## Single-shot acquisition ##
- HDR——即高动态范围图像(High-Dynamic Range，简称HDR)，相比普通的图像，可以提供更多的动态范围和图像细节，根据不同的曝光时间的LDR(Low-Dynamic Range)图像，利用每个曝光时间相对应最佳细节的LDR图像来合成最终HDR图像，能够更好的反映出真实环境中的视觉效果。
- 说白了就是在一张图片中尽可能同时显示最亮和最暗的地方。
- One possible way to incerase the dynamic range of recorded content is to *capture image gradients rather than actual pixel intensities*.
- [ND filter](https://baike.baidu.com/item/ND%E6%BB%A4%E9%95%9C/8465111?fr=aladdin) is an important concept.
- Large, completely saturated regions in the sensor image are usually filled with data interpolated from neighbouring unsaturated regions.
- An aligned spatial light modulator fixed in front of the sensor is an alternative way to mounting a fixed set of ND filters.
> It's difficult to align a DMD with a sensor in a pixel-precise basis, partly due to the requirement of additional relay optics.

- Lower spatial frequencies in the image can be modulated by *Adaptive Dynamic Range Imaging approach*

## Multi-sensor and multi-exposure techniques ##

- **The most straightforward way of acquiring HDR images is
to sequentially capture multiple photographs with different
exposure times and merge them into a single, high-contrast
image**.
- Some of these approaches simultaneously compute the non-linear camera response function from the image sequence.
- There is HDR video.
- Other methods:
> Static filter with varying transmissivity(Generalized Mosaicing)

>











