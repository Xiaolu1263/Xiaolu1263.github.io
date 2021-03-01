---
title: "Wireless Driver Arrival Sensing for Smart Car"
collection: publications
permalink: /publications/3Wireless-Driver-Sensing

---
<style> div.a { line-height: 68%; margin-bottom: -10px;} </style> 

## Abstract
[//]: # <b> 1. What is Driver Arrival Sensing? Why do we need it?</b> <br>
<div class="a"> <b>1. What is Driver Arrival Sensing? Why do we need it? </b>  </div> 
  * Driver-Sensing means that your car knows your arrival time rather just you presence/proximity as most of the existing work does. <br>
  * By enabling driver's arrival time sensing, the car is more smart in multiple-service management. For example, your AC should be turned on earlier since it takes a rather long time to warm/cool your car to a comfortable temperature. However, you may want to open your car door only when you arrives. The control system on the car can be more flexible to arrange the requrested services while reduce the energy consumption if it is able to sense your exact arrival time.

[//]: # <b> 2. How does it work? Is WiFi-FTM available now? </b> <br>
<div class="a"> <b>2. How does it work? Is WiFi-FTM available now? </b>  </div> 
  * We designed the system by using WiFi Fine Time Measurements ([WiFi-FTM](https://people.csail.mit.edu/bkph/ftmrtt_intro), IEEE 802.11mc, 2016) which can provide the distances between 2 WiFi cards with [Meter-accuracy](https://www.gpsworld.com/how-to-achieve-1-meter-accuracy-in-android/) in both [Indoor](https://xiaolu1263.github.io/files/2020-WiFi-RTTIndoor-Positioning.pdf) and [Outdoor](https://xiaolu1263.github.io/files/WiFiRTT_mobicom.pdf) scenarios <br>
  * Google released [WifiRttScan APP](https://play.google.com/store/apps/details?id=com.google.android.apps.location.rtt.wifirttscan&hl=en_US&gl=US) in 2019. More and more [Phones and APs](https://developer.android.com/guide/topics/connectivity/wifi-rtt) can support [IEEE 802.11mc](https://en.wikipedia.org/wiki/IEEE_802.11mc) and [WiFi-FTM](https://people.csail.mit.edu/bkph/ftmrtt_intro)...

[//]: # <b> 3. Have you tested your system using practical measurements? </b>
<div class="a"> <b>3. Have you tested your system using practical measurements? </b>  </div> 
  *  The system has been implemented and ported it into Linux OS for real-world validation in different parking lots and garages in Maryland, which indicates 92.5% accuracy with less than 1s error <br>

For more information, please refer to our paper ([PDF](https://xiaolu1263.github.io/files/DriverSensing.pdf)) <br>

<b> Key words: Driver's Arrival Time Sensing, WiFi-FTM, IEEE 802.11mc.</b>
