---
title: "mmWave-Based Vital Signs Monitoring"
collection: publications
permalink: /publications/3mmWave-Vital-Sign

---

## Abstract
<b> 1. What is Vital Signs Monitoring? Why do we need it?</b> <br>
  * Vital Sign Monitoring System here refers to a Radio System which can accurately estimate the breathing rate, heart rate and heart rate viability (HRV) since they are great [indicators of our body's basic functions](https://www.hopkinsmedicine.org/health/conditions-and-diseases/vital-signs-body-temperature-pulse-rate-respiration-rate-blood-pressure). <br>
  * Traditional ways usually need the users to wear various of sensors such as [Temperature Thermometer](https://en.wikipedia.org/wiki/Medical_thermometer) for body temperature, [strain Sensors](https://www.nature.com/articles/s41746-019-0083-3) for Breathing Rate, [ECG Sensor](https://en.wikipedia.org/wiki/Electrocardiography) for Heart Rate and HRV. Here by a Radio Way, we do not require any wearable sensor but only a mmWave Radar (in the future can be the dense-deployed 5G stations) so that the user can get its Breathing Rate, Heart Rate and HRV at the same time. By enabling such a system in your home, you can build you own health-database without any extrac overhead.

<b> 2. How does it work? Is WiFi-FTM available now? </b> <br>
  * We designed the system by using WiFi Fine Time Measurements ([WiFi-FTM](https://people.csail.mit.edu/bkph/ftmrtt_intro), IEEE 802.11mc, 2016) which can provide the distances between 2 WiFi cards with [Meter-accuracy](https://www.gpsworld.com/how-to-achieve-1-meter-accuracy-in-android/) in both [Indoor](https://xiaolu1263.github.io/files/2020-WiFi-RTTIndoor-Positioning.pdf) and [Outdoor](https://xiaolu1263.github.io/files/WiFiRTT_mobicom.pdf) scenarios <br>
  * Google released [WifiRttScan APP](https://play.google.com/store/apps/details?id=com.google.android.apps.location.rtt.wifirttscan&hl=en_US&gl=US) in 2019. More and more [Phones and APs](https://developer.android.com/guide/topics/connectivity/wifi-rtt) can support [IEEE 802.11mc](https://en.wikipedia.org/wiki/IEEE_802.11mc) and [WiFi-FTM](https://people.csail.mit.edu/bkph/ftmrtt_intro)...

<b> 3. Have you tested your system using practical measurements? </b>
  *  The system has been implemented and ported it into Linux OS for real-world validation in different parking lots and garages in Maryland, which indicates 92.5% accuracy with less than 1s error [PDF](https://xiaolu1263.github.io/files/DriverSensing.pdf)<br>

<b> Key words: Driver's Arrival Time Sensing, WiFi-FTM, IEEE 802.11mc.</b>
