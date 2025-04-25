---
layout: project
title: "3D-printed skin-mimicking flow phantoms"
handle: swir-imaging
image:
category: project
tags: [pulse oximeter, color, skin, pigmentation]
description: "Building multi-layer optical phantoms that mimic skin properties and support pulsatile flow experiments"
---
{% include JB/setup %}

# Premise

To facilitate optical medical device development, it is useful to test devices with optical phantoms that have tissue-matching wavelength-dependent scattering and absorption (µs’, µa). For example there is growing evidence that pulse oximetry is less accurate for patients with pigmented skin. Though the specific mechanism is unknown, understanding how pigmentation impacts oximeter accuracy is critical to determine if algorithms can correct existing oximeters or to inform the design of new equitable oximeters. Phantoms provide a controlled setting for interrogating pulse oximeter function, but pigmentation is not a degree of freedom in commercial phantoms. 

We have [developed a method ][1] for generating flexible resin-based 3D-printed phantoms with <100 µm channels and layer-by-layer variation in optical properties, including pigmentation. We create pulsatile channel expansion with a low-cost syringe pump built from a repurposed 3D printer, and use a commercial Maxim optical analog front end (AFE) reflectance pulse oximeter evaluation system to measure infrared and red photoplethysmogram (PPG) waveforms in phantoms with varying pigmentation. 

<img width="50%" src="/assets/images/presentations/spie2024-pulsatile-phantom.jpg"/>

In addition while many imaging modalities operate in the visible and near infrared (VIS-NIR, 400-1000 nm) range, there is increasing interest in developing short-wave infrared (SWIR, 1000-1700 nm) optical technologies. For example, because melanin absorption decreases significantly from VIS-NIR to SWIR, SWIR imaging (unlike VIS-NIR) offers an equitable pigment-insensitive modality for skin imaging. To facilitate device development, it is useful to test devices with optical phantoms that have tissue-matching wavelength-dependent scattering and absorption (µs’, µa). However methods to generate phantoms that match SWIR skin optical properties are not well established. To address this need, we extend our previous VIS-NIR work with [3D-printed resin-based skin-mimicking phantoms to the SWIR][2].

Through continued development we anticipate that 3D-printed phantoms will provide an accessible and flexible platform that accelerates testing and validation of pulse oximeter performance across the full spectrum of human pigmentation. 

<img width="50%" src="/assets/images/presentations/spie2025-swir-phantom-poster.jpg"/>

[1]:/presentations/presentation/3d_printed_multilayer.md
[2]:/presentations/presentation/swir-3dprinted-phantoms.md