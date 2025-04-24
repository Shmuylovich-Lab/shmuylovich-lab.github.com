---
layout: project
title: "Coaligned thermal, near-infrared, and visible imaging"
handle: vis-nir-lwir
image:
category: project
tags: [thermal imaging]
description: "Ensuring optical coaligment between visible, near-infrared, and long-wave infrared sensors"
---
{% include JB/setup %}

# Premise

Thermal imaging has shown promise in a variety of clinical settings, including diagnosis and monitoring of disease like skin infection and vascular lesions, as well as non-contact monitoring of vital signs like breathing rate and body temperature. While thermal cameras can provide a spatial temperature map, even high spatial resolution thermal cameras lack visible landmarks and thus thermal cameras are typically combined with visible cameras that provide needed visual context. However the visible and thermal camera sensors in existing devices are typically positioned adjacent to each other and not optically coaligned, which creates a parallax effect whereby thermal and visible images are misregistered. Co-registration of visible and thermal images subsequently requires software-based alignment that varies with imaging distance, which creates complex workflows in settings where areas of interest have a range of depths to evaluate or where distance changes during imaging. To overcome this limitation, we developed a low-cost co-aligned visible/near-infrared (VIS/NIR) and thermal imaging system where a Raspberry-Pi NoIR camera was made optically co-axial with a Lepton 3.5 thermal camera by using a 45° beamsplitter consisting of glass coated with Indium Tin Oxide (ITO). ITO has been shown to reflect (80-90%) long-wave infrared (LWIR, 8-12µm) thermal radiation and transmit (>80%) visible to NIR light (400-1000 nm). 

<img width="50%" src="/assets/images/projects/vis-nir-lwir/prototype-schematic.jpg"/>

We have presented our [initial findings][1] and are exploring additional applications of this approach in medically-relevant applictions.

[1]:/presentations/presentation/coaligned_thermal.md
