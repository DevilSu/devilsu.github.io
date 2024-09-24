---
title: "60 GHz SFCW Radar 3D Point Cloud Reconstruction"
subtitle: "Yang-Hsi Su, Alanson Sample"
summary: "Fun backburner project 2, 20 Tx by 20 Rx!"
date: 2021-10-28
cardimage: 2021_60GHz.png
# featureimage: photo1.jpeg
caption: Image caption
# authors:
#   - Christian: author.jpeg
---

{{< youtube id="cMN6qjYsvSA" title="mm-Wave SFCW Radar 3D Point Cloud Reconstruction" autoplay="false" >}}

## mm-Wave 3D PointCloud in Real Time!

{{< dvs_justify_align_text text="Normally radars are FMCW (Frequency Modulated Continuous Wave), this dev kit uses SFCW (Stepped Frequency Continuous Wave), so there is not too much math, paper, code to reference from. I started learning the steering basics from scratch, from 1D ranging, to 2D B-Scan/Scope plot, then to 3D pointcloud calculation. And all implemented in real time, visualized with synced frames from a RealSense camera. The dev kit can go from 60 to 69 GHz with various freqency spacings, but maybe its math or calibration problem, I couldn't get the dev kit to sense object pass 5 meters. Since the dev kit does not give low level control, its hard to debug (or I need more RF knowledge :cry:). But this is also the reason I am doing my own FMCW ultrasound large element microphone array from the ground up. We choose our mics, design our PCB, write FPGA code, and have full control from hardware to software. Technically with current results we can just shove it into ML and publish, but no, good enough real time demos only.">}}