---
layout: project
title: "Short-wave Infrared Imaging"
handle: swir-imaging
image:
category: project
tags: [infrared, swir]
description: "Short wave infared imaging offers a novel approach to quantifying skin disease"
---
{% include JB/setup %}

# Premise

Imaging modalities have the potential to provide objective skin assessment. These modalities often operate in the visible and near-infrared specture, and therefore rely on Silicon (Si)photodetectors which operate in the 400-1100 nm range. Poor performance of Si-based detectors beyond 950nm constrains what these devices can measure because in this spectral range melanin and hemoglobin are the dominant chromophores, while lipid and water are essentially invisible. 

<img width="50%" src="/assets/images/projects/swir-imaging/vis-swir-chromophore.png"/>

In the infrared beyond the reach of Si-based photodetectors (above 1100nm), a different view of cutaneous disease emerges. Here water and lipid absorption becomes significant while melanin continues to decay , and therefore disease processes like
cutaneous inflammation (associated with changes of tissue water or lipid content can be directly measured regardless of the degree of skin-pigmentation. Fortunately in recent years indium gallium arsenide (InGaAs) cameras, sensitive to the short wave infrared (SWIR) from 900-1700nm, have become available. While InGaAs cameras are being actively studied for biology applications this technology is not easily accessible to practicing dermatologists. 

To help direct our work in the SWIR range, we have also [collaborated with colleagues][6] to measure absorption coefficients of skin chromophores directly in the SWIR.

Using a benchtop hyperspectral SWIR imaging system, we [showed][1] that hyperspectral SWIR imaging can be used to quantify the degree of inflammation in allergic contact dermatitis. That work inspired our goal to create a multispectral SWIR imaging device that can be easily used in clinic to better assess skin disease equally well in all patients regardless of skin color. With support from a [DP5 award from the NIH][5], we have built such a multispectral SWIR imaging system, and have validated its ability to detect 1) [intradermal fluid][2] 2) [acne-associated inflammation and lipid][3], and [evidence of bruising][4] in a pigment-insensitive fashion. We continue to enhance system functionality with a focus on portability and usability. 

[1]:/papers/paper/hyperspectral-acd
[2]:/presentation/presentation/swir_fluid
[3]:/presentation/presentation/swir_acne
[4]:/presentation/presentation/mosaic_swine_bruise
[5]:https://reporter.nih.gov/project-details/10254984
[6]:/papers/paper/jove-swir