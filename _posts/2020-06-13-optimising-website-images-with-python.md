---
published: true
date:
  'Sat Jun 13 2020 01:00:00 GMT+0100 (British Summer Time)': null
categories:
  - Personal
tags:
  - Website
  - Programming
  - Python
excerpt_separator: <!--more-->
analytics:
  provider: google-gtag
  google:
    tracking_id: UA-168799890-2
    anonymize_ip: false
title: Optimising website images with Python
---
Previously I had downloaded all the images from my Medium posts with [medium-2-md](https://www.gautamdhameja.com/medium-to-markdown-converter/) and then added custom images to this website. I then plugged my site into Google's [Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/) to see how my website was fairing.

Desktop speed was looking good.

![image-center](/assets/images/desktop_before_opti.PNG){: .align-center}

Mobile.... not so good.

![image-center](/assets/images/mobile_before_opti.PNG){: .align-center}

So off I went to find a way to optimise all my images, which led me to [optimize-images](https://pypi.org/project/optimize-images/) written in Python. I'm a simple man and so was the module. I ran it through the command line and selected my folder full of images I had got off Medium.

To install:

`pip3 install pillow optimize-images`

Choose folder path filling in the blanks afetr ./:

`optimize-images ./`

After that I re-uploaded my now optimised images to GitHub. As you can see the results were pretty good for desktop.

![image-center](/assets/images/desktop_after_opti.PNG){: .align-center}

And brilliant for mobile!

![image-center](/assets/images/mobile_after_opti.PNG){: .align-center}
