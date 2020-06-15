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
title: Optimising images for your website with Python
---
In the process of [making a new personal website](https://naiyanjones.com/personal/how-i-built-this-website/) I downloaded all my [Medium posts](https://medium.com/@naiyanjones) with  [medium-2-md](https://www.gautamdhameja.com/medium-to-markdown-converter/).

After I was all done porting posts across I plugged my website into Google's [Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/) to see how my website was fairing.

Desktop speed was looking good.

![image-center](/assets/images/desktop_before_opti.PNG){: .align-center}{: .align-center}{:height="45%" width="45%"}

Mobile.... not so good.

![image-center](/assets/images/mobile_before_opti.PNG){: .align-center}{: .align-center}{:height="45%" width="45%"}

The culprit? Some very large image sizes. Seriosuly look at that 1.7 seconds and banner size.

![image-center](/assets/images/google_pageppeed_insights.PNG){: .align-center}{: .align-center}{:height="45%" width="45%"}

So off I went to find a way to optimise all my images, which led me to [optimize-images](https://pypi.org/project/optimize-images/) written in Python. I'm a simple man and so was the module. I ran it through the command line and selected my folder full of images.

To install:

`pip3 install pillow optimize-images`

Choose folder path filling in the blanks after `./`:

`optimize-images ./`

After that I re-uploaded my now optimised images to GitHub. As you can see the results were pretty good for desktop.

![image-center](/assets/images/desktop_after_opti.PNG){: .align-center}{: .align-center}{:height="45%" width="45%"}

And brilliant for mobile!

![image-center](/assets/images/mobile_after_opti.PNG){: .align-center}{: .align-center}{:height="45%" width="45%"}

So there we have it. Optimising images with Python through command line resulting in much higher page speeds and webstite optimisation.
