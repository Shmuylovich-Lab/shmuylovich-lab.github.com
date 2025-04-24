---
layout: project
title: "Skin color assessment"
handle: swir-imaging
image:
category: project
tags: [color, melanin, hemoglobin, colorimetry, spectroscopy, monte-carlo]
description: "Objective assessment of the components of skin that determine skin color"
---
{% include JB/setup %}

# Premise

Skin color is determined by a complex interplay between light and skin constituents like hemoglobin and melanin. While skin color is often assessed subjectively, subjective approaches are subject to bias and do not provide quantitative measures of skin constituent properites. Objective measurements of skin include diffuse reflectance spectroscopy and colorimetry and have the potential to overcome the limitations fo subjective measures. However the tools available for objective skin color assessment are often tools built for industrial applications and repurposed for skin, and therefore are costly, bulky, and effectively inaccessible for widespread clinical use. 

Furthermore, the connection between objectively-determined skin measurements and skin properties poses a challenge of interpretability. For example a colorimeter or spectrophotometer may be used to determined a reflectance spectrum or LAB colorspace coordinates for a given area of skin, and while parameters like the individual typology angle (ITA) or melanin index (MI) can be calculated from these objective measures and are often used as surrogates for skin melanin content, a change in skin blood content can shift these calculated parameters (even while melanin remains constant). Thus current measurements that are established objective surrogates for melanin are confounded by tissue blood volume.

We seek to address this problems through several avenues. First we have [utilized physics-based models of light-tissue interaction to determine the causal connection between skin constituents][1] (melanin and hemoglobin content) and colorimetric measurements (reflectance curves and LAB color space). This allows us to mathematically predict how reflectance spectra and LAB color space coordinates will shift in the face of constant pigmentation and varying blood volume and vice versa, and these insights can be used to derive improved approaches to extracting measures of melanin that are decoupled from blood volume. 
<img width="50%" src="/assets/images/presentations/spie2025-causal-lab.jpg"/>

In addition, we are exploring alternative aproaches included laser-stimulated thermal imaging and photography-based approaches to skin color assessment. Specifically, we have developed a skin-specific color [calibration target][2] that is compatible with the 10x epilumination cross-polarized clinical dermatoscope and can be used to achieve accurate assessment of the LAB color space coordinates of skin through photography alone.


<img width="50%" src="/assets/images/presentations/spie2025-dermoscope-color.jpg"/>



[1]:/presentations/presentation/causal_LAB
[2]:/presentations/presentation/color_calibrated_dermoscopy
