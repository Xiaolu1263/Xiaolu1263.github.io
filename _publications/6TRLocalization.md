---
title: "Time Reversal Based Localization and Tracking"
collection: publications
permalink: /publications/6TRLocalization

---

## Abstract
<b> 1. What is Time Reversal? </b> <br>
  * Time reversal (TR) is a fundamental physical phenomenon that takes advantage of an unavoidable but rich multipath radio propagation environment to create a spatial-temporal resonance effect, the so-called **focusing effect** (refer to [Why Time Reversal](https://xiaolu1263.github.io/files/WhyTimeReversal.pdf)).
  * Mathematically, the TR effect is simply for the environment to serve as the computer to perform a perfect deconvolution that is, the environment behaves like a matched filter!. 

<b> 2. How to leverage Multipath? </b> <br>
  * As stated, TR takes adavatage of the environment to constructively add all the radio signal components (both LoS and multipath) in a specific location at a specific timestamp (**focusing effect**). We design the transimitting signal as the TR version of the Forward-Echo. As a result, the transmitting signal will focus on the target and thus improving the SNR greatly. In this sense, TR works like a waveguide which navigates the transimitting power to illuminate on the target. As the **focusing effect** is constructed by the massive signal components, the more the multipath component is, the better the **focusing effect** will be.

<b> 3. How much impovement by using Time Revresal? </b>
  * It is hard to quantilize the SNR improvement since it is also related to the bandwidth, multipath power profile...([TR focusing](https://xiaolu1263.github.io/files/1WaveformingTR.pdf)). However, when we applied TR for DOA estimations with **rich multipath distortions**, the TR based algorithm can achieve the same performace as the traditional ones with lower SNR up to 5dB, which implicitly indicates the superiority of TR in dealing multipath.  <br>

For more details. please refer to our paper ([PDF](https://xiaolu1263.github.io/files/TAES.pdf)）

<b> Key words: Time Reversal, Multipath, Focusing Effect, DOA, Match Filter.</b>
