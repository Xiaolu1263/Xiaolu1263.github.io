---
title: "mmWave-Based Vital Signs Monitoring"
collection: publications
permalink: /publications/4mmWave-Based-Vital-Sign

---

## Abstract
<b> 1. What is Vital Signs Monitoring? Why do we need it?</b> <br>
  * Vital Sign Monitoring System here refers to a Radio System which can accurately estimate the breathing rate, heart rate and heart rate viability (HRV) since they are great [indicators of our body's basic functions](https://www.hopkinsmedicine.org/health/conditions-and-diseases/vital-signs-body-temperature-pulse-rate-respiration-rate-blood-pressure). <br>
  * Traditional ways usually need the users to wear various of sensors such as [Temperature Thermometer](https://en.wikipedia.org/wiki/Medical_thermometer) for body temperature, [strain Sensors](https://www.nature.com/articles/s41746-019-0083-3) for Breathing Rate, [ECG Sensor](https://en.wikipedia.org/wiki/Electrocardiography) for Heart Rate and HRV. Here by a Radio Way, we do not require any wearable sensor but only a mmWave Radar (in the future can be the dense-deployed 5G stations) so that the user can get its Breathing Rate, Heart Rate and HRV at the same time. By enabling such a system in your home, you can build you own ***Health-Database*** without any extrac overhead.

<b> 2. How does it work?  </b> <br>
  * We designed the system by using mmWave since human breathing will cause the movement of chest (or abdomen/belly) ranging from [4-12mm](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4035586/) ([PDF](https://xiaolu1263.github.io/files/2014-ChestMovment.pdf)) with frequency of 6-30 breaths per minute (BPM) while Heart Rate is motivated by your Heart Pumping with a range of [0.2-0.5mm](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4035586/) ([PDF](https://xiaolu1263.github.io/files/2014-ChestMovment.pdf)) in a frequency of 50-120 beats per minute (BPM).

<b> 3. Have you tested your system using practical measurements? </b>
  *  The system has been implemented and ported it into Linux OS for real-world validation in different parking lots and garages in Maryland, which indicates 92.5% accuracy with less than 1s error [PDF](https://xiaolu1263.github.io/files/DriverSensing.pdf)<br>

<b> Key words: Driver's Arrival Time Sensing, WiFi-FTM, IEEE 802.11mc.</b>
