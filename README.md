# Awesome-ISP
A curated list of ISP good stuff. This list can contain anything related to the ISP and welcome pull requests.

## Content
- [Tutorials, books & examples](#tutorials--books---examples)
  * [Tutorials](#tutorials)
  * [Books](#books) 
  * [Examples](#examples)
- [Open Source Camera Driver](#open-source-camera-driver)
- [Camera Pipeline](#camera-pipeline)
  * [Raw data decoder](#raw-data-decoder)
  * [BLC](#blc)
  * [LSC](#lsc)
  * [DPC](#dpc)
  * [Demosaic](#demosaic)
  * [CCM](#ccm)
  * [CSC](#csc)
  * [NR](#nr)
  * [HDR/Tone Mapping](#hdr-tone-mapping)
- [3A Algorithm](#3a-algorithm)
  * [AE](#ae)
  * [AF](#af)
  * [AWB](#awb)
- [Image Quality Tuning](#image-quality-tuning)

## Tutorials, books & examples
### Tutorials
### Books
[Image sensors and signal processing for digital still cameras -- Junichi Nakamura](https://last.hit.bme.hu/download/firtha/video/Sensors/Junichi%20Nakamura%20Image%20sensors%20and%20signal%20processing%20for%20digital%20still%20cameras%20%202006.pdf)  
[Image Processing for Embedded Devices -- Sebastiano Battiato](https://books.google.com/books/about/Image_Processing_for_Embedded_Devices.html?id=K5aOhnvGJToC)  
[Theory and Applications of Smart Cameras -- Kyung Chong-Min](https://www.springer.com/gp/book/9789401799867)  
### Examples
openISP -- Open Image Signal Processor [[code]](https://github.com/cruxopen/openISP)  
fast-openISP -- Fast Open Image Signal Processor [[code]](https://github.com/QiuJueqin/fast-openISP)  
camera-pipeline -- A Software Platform for Manipulating the Camera Imaging Pipeline [[code]](https://karaimer.github.io/camera-pipeline/)  
ISP Pipeline -- Algorithms of ISP Pipeline [[code]](https://gitee.com/wtzhu13/ISPAlgorithmStudy)  
## Open Source Camera Driver
V4L2 -- Video4Linux (V4L for short) is a collection of device drivers and an API for supporting realtime video capture on Linux systems [[code]](https://www.kernel.org/doc/html/v4.9/media/uapi/v4l/v4l2.html)  
HAL -- Android's camera hardware abstraction layer [[code]](https://source.android.com/devices/camera)  
libcamera -- A complex camera support library for Linux, Android, and ChromeOS [[code]](https://github.com/kbingham/libcamera)  
## Camera Pipeline
### Raw data decoder
MatRaw -- Read and Process Camera Raw Data with MATLAB [[code]](https://github.com/QiuJueqin/MatRaw)   
dcraw -- Decoding raw digital photos in Linux [[code]](https://github.com/ncruces/dcraw)  
LibRaw -- Library for reading and processing of RAW digicam images [[code]](https://github.com/LibRaw/LibRaw)  
### BLC
### LSC
lens_shading -- Lens shading analysis tool [[code]](https://github.com/6by9/lens_shading)  
lens_shading_editor -- Raspberry Pi camera lens shading table editor [[code]](https://github.com/dridri/lens_shading_editor)   
### DPC
### Demosaic
High-Quality Linear Interpolation for Demosaicing of Bayer-Patterned Color Images [[code]](https://www.microsoft.com/en-us/research/publication/high-quality-linear-interpolation-for-demosaicing-of-bayer-patterned-color-images/)  
Residual Interpolation for Color Image Demosaicking [[code]](http://www.ok.sc.e.titech.ac.jp/res/DM/RI.html)  
### CCM
Camera Color Correction Toolbox [[code]](https://github.com/QiuJueqin/color-correction-toolbox)  
Colour Correction Toolbox for AIC 2017 submission [[code]](https://github.com/fangfufu/Colour_Correction_Toolbox)  
Compute color correction matrix [[code]](https://github.com/lighttransport/colorcorrectionmatrix)  
### NR
### HDR/Tone Mapping
## 3A Algorithm
### AE
### AF
### AWB
A comparison of computational color constancy algorithms [[Project Page]](http://kobus.ca/research/programs/colour_constancy/)  
Illumination Chromaticity Estimation using Inverse-intensity Chromaticity Space [[Code]](https://tanrobby.github.io/code/iic.zip) [[Project Page]](https://tanrobby.github.io/research/lightchroma/results.html)  
Edge-Based Color Constancy [[Project Page]](https://ivi.fnwi.uva.nl/isis/publications/bibtexbrowser.php?key=vandeWeijerTIP2007&bib=all.bib)
## Image Quality Tuning
