---
title: "TomoID: A Scalable Approach to Device Free Indoor Localization via RFID Tomography"
subtitle: "Yang-Hsi Su, Jingliang Ren, Zi Qian, David Fouhey, and Alanson Sample"
summary: "INFOCOM 2023, MAY@NYC"
date: 2023-05-20
cardimage: 2023_TomoID_RP.jpg
# featureimage: photo1.jpeg
caption: Image caption
# authors:
#   - Christian: author.jpeg
---

{{< youtube id="dxr-rFkBDtQ" title="TomoID: A Scalable Approach to Device Free Indoor Localization via RFID Tomography" autoplay="false" >}}

Link to the paper: https://ieeexplore.ieee.org/document/10228938 [:page_facing_up:](https://theisclab.com/docs/2023_INFOCOM_TomoID_SU.pdf)

## Abstract
{{< dvs_justify_align_text text="Device-free localization methods allow users to benefit from location-aware services without the need to carry a transponder. However, conventional radio sensing approaches using active wireless devices require wired power or continual battery maintenance, limiting deployability. We present TomoID, a real-time multi-user UHF RFID tomographic localization system that uses low-level communication channel parameters such as RSSI, RF Phase, and Read Rate, to create probability heatmaps of users’ locations. The heatmaps are passed to our custom-designed signal processing and machine learning pipeline to robustly predict users’ locations. Results show that TomoID is highly accurate, with an average mean error of 17.1 cm for a stationary user and 18.9 cm when users are walking. With multi-user tracking, results showing an average mean error of <72 cm for five individuals in constant motion. Importantly, TomoID is specifically designed to work in real-world multipath-rich indoor environments. Our signal processing and machine learning pipeline allows a pre-trained localization model to be applied to new environments of different shapes and sizes, while maintaining good accuracy sufficient for indoor user localization and tracking. Ultimately, TomoID enables a scalable, easily deployable, and minimally intrusive method for locating uninstrumented users in indoor environments.">}}


### Note
{{< dvs_justify_align_text text="Oh god this paper took forever to get out the door. Huge thanks to Jack and David for all the help on the ML pipeline, and those IMWUT reviewers that gave two major revisions and then a desk reject. I think I worked on this for too long and forget how amazing this demo is. ">}}