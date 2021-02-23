---
title: "RF-based Indoor Tracking System"
collection: publications
permalink: /publications/7RF-Indoor-Tracking

---

## Abstract
<b> 1. What challenges are there for Indoor Tracking? </b> <br>
  * Unavoidable multipath distortions makes the typical DOA/AOA/TOF methods failed.
  * The popular [GPS](https://en.wikipedia.org/wiki/Global_Positioning_System) cannot work well also due the lack of LoS singals to the GPS satellites

<b> 2. How do you solve the Multipath issue? </b> <br>
  * We treat LoS and NLoS signal as a whole and explore the statistical property of the received signal by analog to the [TR principle](https://xiaolu1263.github.io/publications/5MassiveMIMOLocalization). We prove that the TR is mathematically equivalent to the **the autocorrelation function of the CSI (ACF)**. the received signal in massive MIMO systems exhibits like a stable Sinclike focusing beam around the receiver in spatial domain. By using ACFS, we bypass the problem that the ***LOS and NLOS signals are hard to be distinguished*** in severe NLOS environments.

<b> 3. What is advantages of using ACFS? </b>
  *  Variation of the imping angle/delay of each specific signal component (regardless of LOS and NLOS) caused by the channel changes (e.g., target movement may cause the changes of wireless channel between the BSs and target) does not impact much about our algorithm since the statistical property of the ACFS is stable. 
  * The system leverages the existing massive antennas on the BSs and only 1 antenna is needed on the receiver side, which makes it a low-cost design.
  * The system can support massive concurrent targets/clients without affecting the channel capacity and preserve privacy since a target/client only listen to the BSs without transmitting any signal.
  * Owing to the benifit of using ACFS, the system robustly achives < 0.2m localization error regardless of the environments and thus making the it scalable to various of applications such as navigations.
<br>

<b> Key words: Massive MIMO, Time Reversal, Multipath, Localization and Tracking.</b>
