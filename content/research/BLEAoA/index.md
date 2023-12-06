---
title: Single Packet, Single Channel, Switched Antenna Array for RF Localization
subtitle: "Yang-Hsi Su, Chouchang (Jack) Yang, Euiseok Hwang, and Alanson P. Sample"
summary: "UBICOMP 2023, OCT@CANCUN"
date: 2023-10-10
cardimage: 2023_TomoID_RP.jpg
# featureimage: photo1.jpeg
caption: Image caption
# authors:
#   - Christian: author.jpeg
---

{{< youtube id="lUnYgUUuC0w" title="Single Packet Radio Localization" autoplay="false" >}}

Link to the paper: https://dl.acm.org/doi/10.1145/3596263 [:page_facing_up:](https://theisclab.com/docs/2023_IMWUT_SinglePacketAoA_SU.pdf)

## Abstract
{{< dvs_justify_align_text text="Cost-effective and accurate means of localizing radio transmitters has the potential to enable a wide range of applications in the consumer electronics, IoT, and healthcare domains. However, existing multi-antenna localization methods require high-cost synchronized receivers, long integration times, and/or specialized packet structures. This paper proposes using a high-speed RF mux that sequentially connects antennas to a single 2MHz radio receiver and sub-packet switching to determine the Angle of Arrival of individual packets. Importantly, this approach does not need synchronization between the mux and the receiver, reducing cost and system complexity. Our signal processing pipeline recovers both switch timing and the antenna number from the received RF signal. The sub-packet waveforms are used to generate a synthetic reference packet, and our customized Multi-Resolution Beaming and MUSIC algorithms are used to determine the Angle of Arrival. Results show that our real-time system is highly accurate even when the target is moving, with a mean AoA accuracy of 3.4 degrees and a 2D localization accuracy of 36.4 cm. Furthermore, the system is capable of tracking multiple users carrying smartphones in either their hands or pockets. Ultimately this approach enables a single low-cost, low bandwidth commodity RF receiver to be used to create an N-element phased array receiver.">}}