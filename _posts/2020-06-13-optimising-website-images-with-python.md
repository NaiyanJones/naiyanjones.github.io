---
published: true
date:
  'Sat Jun 13 2020 01:00:00 GMT+0100 (British Summer Time)': null
categories:
  - Technology
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

![image-center](/assets/images/Google PageSpeed Insights.PNG){: .align-center}

So off I went to find a way to optimise all my images, which led me to [optimize-images](https://pypi.org/project/optimize-images/). A Python module which you can run through the command line. All you have to do is select an image or folder containing images.  

To install:

`pip3 install pillow optimize-images`

Choose folder path filling in the blanks after `./`:

`optimize-images ./`

After that I re-uploaded my now optimised images to GitHub. As you can see the results were pretty good for desktop.

![image-center](/assets/images/desktop_after_opti.PNG){: .align-center}{: .align-center}{:height="45%" width="45%"}

And brilliant for mobile!

![image-center](/assets/images/mobile_after_opti.PNG){: .align-center}{: .align-center}{:height="45%" width="45%"}

So there we have it. Optimising images with Python can be very quick and painless with massive gains for website speed, especially on mobile.
