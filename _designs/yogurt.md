---
title: "Yogurt, to visualize your browsing behavior"
layout: project
img_url: /assets/project_img/yogurt_thumb.jpg
description: Inspired by the concept of encrypted self-portrait in DNA art, it is a Google Chrome Extension we built to help people be aware of their browsing behavior
date: "2012-12-10"
---


> _a CS448b Data Viz project finished at Stanford._


<br>
## When online distraction becomes a lifestyle

No matter whether people like it or not, Today’s Internet has already been the new habitat for human, dramatically changing. our everyday life patterns.

When empowered with efficiency by ubiquitous online tools, or be enlightened with volume by unlimited access to resource, everyone cherishes the significant convenience that this trend of internet booming is brining to us. 

In the meanwhile, however, more people have realized that Internet is also a rabbit hole of distraction. It’s very easy to wind up knee-deep in random videos or reddit discussions when you intended only to answer a few e-mails. Distraction theorists even claim that connected devices destroy our ability of deep thinking about actual meaning and beauty. Similar theories have also been supported by studies in research institutes and universities.

Well, what can we do, when all of this become a inevitable part of our everyday life?

<br>
## At least we can be consciousness about our behavior

Many people have started working against online distractions. Some brutally shut down the access to internet, while others only display plain charts about people's time spending online.

We found the former methods are easily abandoned or bypassed by users due to strong antipathy, the latter are too minor for their attention.

What about If have something less brutal yet engaging enough as a reminder? A idea occurred to us with following elements:

1. **a Non Intrusive yet Obvious Reminder** of distraction widget;
2. **a Engaging Visualization** of browsing history;
3. **some Detailed Analysis** about user’s attention shift while online.

<br>
## A DataViz browser extension to remind you of better time management


![Yogurt screenshot]({{ "/assets/project_img/yogurt_draft.jpg" | absolute_url }})_Preliminary Concept Sketch_


Yogurt is a browser extension (available for [Chrome](https://chrome.google.com/webstore/detail/yogurt/bkcllpfdmadccnllfpkeipobfhclbjnf) and Firefox) implementing barcode chart to visualize browsing history of selected websites with the associated level of interest configured by the user.

 <p><style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'>    <iframe title="YouTube video player" width="640" height="390" src="http://www.youtube.com/embed/x92nYIW9354" frameborder="0" allowfullscreen></iframe></div></p>


The barcode chart, inspired by the concept of encrypted self-portrait in DNA art, is rendered using SVG element + WebSQL storage, Smooth interactions are appended for user to reveal detailed information.

![Yogurt screenshot]({{ "/assets/project_img/yogurt_1.jpg" | absolute_url }})_Visualization Panel_


A configuration panel helps user to input personalized level of distraction to different domains, and to define the time length 

![Yogurt config panel screenshot]({{ "/assets/project_img/yogurt_config_1.jpg" | absolute_url }})
![Yogurt config panel screenshot]({{ "/assets/project_img/yogurt_config_2.jpg" | absolute_url }})_The Configuration Panel_

A widget hovers over at the corner of the webpage user is focusing on, with color coded indicator to tell 

![Yogurt config panel screenshot]({{ "/assets/project_img/yogurt_popup.jpg" | absolute_url }})_The Widght You Can Always See_


This project was accepted to 2013 UIST Post Track, [Visualizing Web Browsing History with Barcode Chart](http://bwang29.github.io/files/yogurt_submit_final.pdf)

![Yogurt config panel screenshot]({{ "/assets/project_img/yogurt_UIST_poster.jpg" | absolute_url }})_UIST Poster_

It was the final project developed in CS448B Data Viz. It was done with [Borui Wang](http://bwang29.github.io/), [Jianfeng Hu](https://www.linkedin.com/in/jianfenghu/), and [Ningxia Zhang](http://ningxiazhang.com/).


