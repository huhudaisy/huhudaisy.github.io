---
layout:     post
title:      "	A 56 Gb/s PAM4 Transceiver "
subtitle:   "with novel coding and FFE"
date:       2019.09.15
author:     "qianting"
header-img: "img/in-post/tag-bg.jpg"
catalog: True
tags:
    - Postgraduate
---

##  A 56 Gb/s Parallel Link PAM4 Transceiver. July. 2018 –July. 2019
The rapid development of cloud computing and artificial intelligence has necessitated the operation of transceivers at 56 Gb/s or higher data rates. Furthermore, owing to its double bandwidth efficiency, four-level pulse amplitude modulation (PAM4) signalling is replacing non-return-to-zero (NRZ) signalling for ultra-high speed rate transceiver. The principle of traditional equalisers, such as the  CTLE, FFE, and DFE, that are used to eliminate inter-symbol interference (ISI) is based on compensation of high-frequency-attenuation. As the frequency increases, the compensation becomes more difficult, and the circuit becomes more sophisticated. Analysis on the latest transceivers in ISSCC shows that most transceivers applied with traditional equalisers can eliminate less than 20dB channel loss at 56Gb/s and less than 10dB at 100Gb/s.

This work proposes a novel coding scheme, alternately differential coding (DC), which helps traditional equalisers break through the limitation of compensation. The DC makes two links transmit identical data at the previous unit interval (UI), and the complementary data at the current UI, which eliminates the first post-cursor ISI in the time domain. Moreover, since the coding scheme is based on differential links, it offers unique advantages, such as low power-supply noise and high noise immunity . DC equalisation has strong adaptability to different data frequencies and various channels. We presented a design of a 54 Gb/s PAM4 transceiver which combined with DC and 2−tap FFE, and can successfully equalised 20 dB channel loss at 56 Gb/s. Implemented in a 14 nm FinFET technology, this transceiver has taped out.

![](/img/in-post/transceiver/eyediagram.jpg)
