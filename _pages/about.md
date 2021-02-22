---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Xiaolu Zeng | 曾小路
======
Postdoc Research Associate
<br /> 
 [Department of Electrical & Computer Engineering University of Maryland, College Park](https://www.umd.edu/)
 <br /> 
 Principal Data Scientist
  <br /> 
 [Origin Wireless AI](https://www.originwirelessai.com/)

:briefcase: Research Projects
======
<b> 1.  Device-free Wireless Monitoring System </b> <br />
  :small_blue_diamond: A device-free motion sensing system, which won the [CES 2020 Innovation Award](https://www.ces.tech/Innovation-Awards/Honorees/2020/Honorees/L/Linksys-Aware.aspx)  <br /> 
<b> 2. Wireless Vital Signs Detection System </b> <br />
  :small_blue_diamond: Remote Patient Monitoring, which won the [CES 2021 Best of Innovation Award](https://www.ces.tech/Innovation-Awards/Honorees/2021/Best-Of/O/Origin-Health-Remote-Patient-Monitoring.aspx)  <br /> 
<b> 3. Wireless Driver Arrival Sensing for Smart Car </b>  <br />
  :small_blue_diamond: Your car knows when you are going to arrive (WiFi-FTM, IEEE 802.11mc, 2016)   <br /> 
<b> 4. mmWave-Based Vital Signs Monitoring </b> <br />
  :small_blue_diamond: Know your  breathing rate, heart rate and heart rate viability (HRV) with no wearables <br /> 
<b> 5. 5G Massive MIMO for Localization and Tracking </b> <br />
  :small_blue_diamond: Decimeter-accuracy regardless of multipath distortions in dynamic environments <br />
<b> 6. Time Reversal Based Localization and Tracking </b> <br />
  :small_blue_diamond: Time Reversal turns multipath distortions to friend for target localization and tracking. <br />
<b> 7. RF-based Indoor Tracking System </b> <br />
  :small_blue_diamond: Calibration-free and Decimeter-accuracy Indoor Tracking Systems <br />


Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory). 

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
