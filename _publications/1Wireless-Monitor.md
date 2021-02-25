---
title: "Device-free Wireless Monitoring System"
collection: publications
permalink: /publications/1Wireless-Monitor

---

## Abstract
<style>
ul.a {list-style-type: circle;}
ul.b {list-style-type: disc;}
ul.c {list-style-type: square;}
ol.d {list-style-type: armenian;}
ol.e {list-style-type: cjk-ideographic;}
ol.f {list-style-type: decimal;}
ol.g {list-style-type: decimal-leading-zero;}
ol.h {list-style-type: georgian;}
ol.i {list-style-type: hebrew;}
ol.j {list-style-type: hiragana;}
ol.k {list-style-type: hiragana-iroha;}
ol.l {list-style-type: katakana;}
ol.m {list-style-type: katakana-iroha;}
ol.n {list-style-type: lower-alpha;}
ol.o {list-style-type: lower-greek;}
ol.p {list-style-type: lower-latin;}
ol.q {list-style-type: lower-roman;}
ol.r {list-style-type: upper-alpha;}
ol.s {list-style-type: upper-greek;}
ol.t {list-style-type: upper-latin;}
ol.u {list-style-type: upper-roman;}
ol.v {list-style-type: none;}
ol.w {list-style-type: inherit;}
</style>

<ol>
<li><b> How can we bridge the object motion with the wireless signal? </b></li>
  <ul class="b">
    <li>The movement of a object embedded in the environment will casue corresponding changes in the [Wireless Channel Station Information (CSI)](https://en.wikipedia.org/wiki/Channel_state_information). As a result, intuitively, we can extract the object motion from the measured CSI of Wireless Links. Luckily, most of the WiFi devices support/provide CSI out put now such as [Intel 5300](https://www.intel.com/content/www/us/en/products/docs/wireless-products/ultimate-n-wifi-link-5300-brief.html), [Marvell 88W8897](https://www.marvell.com/content/dam/marvell/en/public-collateral/wireless/marvell-wireless-88w8897-product-brief-2018-10.pdf)...</li>
  </ul>
<li><b> How do get rid of multipath distortions since it is alomost everywhere? </b></li>
  <ul class="b">
    <li>We do not have to. By using [Time Reversal](http://video.cmsworldwide.com/SP17/SP17_RayLiu_Keynote_1080p.mp4) techniques, we can leverage the multipath components by exploring the statistical property of the received electromagnetic (EM) signals. In other words, we treat LoS and NLoS signals as a whole. Thus, multipath is not a problem at all.</li>
  </ul>
<ol>
