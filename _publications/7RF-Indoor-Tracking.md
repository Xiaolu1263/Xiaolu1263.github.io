---
title: "RF-based Indoor Tracking System"
collection: publications
permalink: /publications/7RF-Indoor-Tracking

---

## Abstract
<b> 1. What challenges are there for Indoor Tracking? </b> <br>
  * Unavoidable multipath distortions makes the typical DOA/AOA/TOF methods failed.
  * The popular [GPS](https://en.wikipedia.org/wiki/Global_Positioning_System) cannot work well also due the lack of LoS singals to the GPS satellites.

<b> 2. How do you solve the Multipath issue? </b> <br>
  * We treat LoS and NLoS signal as a whole and explore the statistical property of the received signal by analog to the [TR principle](https://xiaolu1263.github.io/publications/6TRLocalization). We proved that the TR is mathematically equivalent to the **the autocorrelation function of the CSI (ACF)**. Thus, by considering the [Raleigh Fading](https://en.wikipedia.org/wiki/Rayleigh_fading), we further proved that the ACF exhibits like a **Focusing Ball** around the receiver in spatial domain. This **Focusing Ball** is then used to develop the Active Tracking System ([see paper of our group](https://xiaolu1263.github.io/files/Feng2018FocusingBall.pdf)).

<b> 3. Does it work for collocated WiFi deployment? </b>
  *  Yes. By exploiting the statistical theory of electromagnetic (EM) waves, we establish a link between the autocorrelation function (ACF) of the physical layer **CSI** and the speed of a moving object, which embraces the rich-scattering environment typical for indoors to facilitate highly accurate Passive Speed Estimation ([see paper of our group](https://xiaolu1263.github.io/files/Feng2018WiSpeed.pdf)). 

<b> 4. Have you tested your system in practical scenarios? </b>
  *  The active one is being commercialized to track a moving object in supermarkets while the passive one is being commercialized as a fall-detector and Gait Recognition, which have been invited for demo to Apple, HP, Qualcomm, Verizon, Marvell. <br>

For more information, please refer to our ([Patent: EP3695783](https://patentscope.wipo.int/search/en/detail.jsf?docId=EP302862678&docAn=20157771))


<b> Key words: Massive MIMO, Time Reversal, Multipath, Localization and Tracking.</b>
