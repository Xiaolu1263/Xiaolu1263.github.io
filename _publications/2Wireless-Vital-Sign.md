---
title: "Wireless Vital Signs Detection System"
collection: publications
permalink: /publications/2Wireless-Vital-Sign

---
<style> div.a { line-height: 68%; margin-bottom: -10px;} </style> 

## Abstract
[//]: # <b> 1. How can we bridge the Vital Sign (Breathing Rate) with the wireless signal? </b> <br>
<div class="a"> <b>1. How can we bridge the Vital Sign (Breathing Rate) with the wireless signal? </b>  </div> 
  * Human breathing will cause the movement of chest (or abdomen/belly) ranging from [4-12mm](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4035586/) ([PDF](https://xiaolu1263.github.io/files/2014-ChestMovment.pdf)) with frequency of 6-30 breaths per minute (BPM). Moreover, the chest movement will induce corresponding [CSI](https://xiaolu1263.github.io/publications/Wireless-Monitor) changes, which can then be measured by WiFi Links. As a result, we can extract the chest movement (a.k.a. Breathing Rate) from the measured CSI. 

[//]: # <b> 2. Can CSI really measure chest movement since it is very weak? </b> <br>
<div class="a"> <b>2. Can CSI really measure chest movement since it is very weak? </b>  </div> 
  * Yes the CSI changes caused by breathing rate is very weak. However, we have multiple subcarriers for both [2.4GHz & 5GHz](https://en.wikipedia.org/wiki/List_of_WLAN_channels) with whatever bandwidth ([usually, 20MHz, 40MHz, 80MHz](https://en.wikipedia.org/wiki/List_of_WLAN_channels)). As a result, we design a subcarrier selection method and futher using a [maximum-ratio combining (MRC)](https://en.wikipedia.org/wiki/Maximal-ratio_combining#:~:text=In%20telecommunications%2C%20maximum%2Dratio%20combining,noise%20level%20in%20that%20channel.) to boost the vital signs. 

[//]: # <b> 3. Have you tested your system using practical measurements? </b>
<div class="a"> <b>3. Have you tested your system using practical measurements? </b>  </div> 
  *  The research was then developed as a Sleep Monitoring System and commercialized as Origin Health for Remote Patient Monitoring by [Origin Wireless AI Inc.](https://www.originwirelessai.com/), which won the [CES 2021 Best of Innovation Award](https://www.ces.tech/Innovation-Awards/Honorees/2021/Best-Of/O/Origin-Health-Remote-Patient-Monitoring.aspx). <br>

<b> Key words: Vital Signs, CSI, Sleep Monitoring.</b>
