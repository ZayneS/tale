---
title: "HappyLabel, a Pick-n-Boom game to tag images of cars"
layout: project
img_url: /assets/project_img/happylabel_thumb.jpg
description: We intended to mix the effort of human computation from people who play the game with intelligence from domain experts who defined the category structure.
date: "2014-5-10"
---

![Yogurt screenshot]({{ "/assets/project_img/happylabel_thumb.jpg" | absolute_url }})


## A preparatory work for design feature training.
Happy label was a crowdsourcing image labeling game inspired by the Game with a Purpose (GWAP) , It was the final project of <a href="https://hcicourses.stanford.edu/cs376/2017/" target="blank">CS376 Human Computer Interaction Research</a>. [Yinan Na](https://www.linkedin.com/in/nayinan/) and I spent amazing four weeks together to build the game and test among students.

We created a human computation game, with the predefined category structure provided, and tested online to see if it can improve the efficiency, label quality and fun to play.

This game was also a preparatory work for vehicle design prediction. We intended using GWAP to label car images for aesthetic design feature training.

<br>

## Game with a Purpose

<a href="https://www.cs.cmu.edu/~biglou/GWAP_CACM.pdf" target="blank">ESP games</a> has been proved with significant result in human involved image tagging activities. Previous studies on ESP games, however, has shown the _**"Obvious"**_ issue: people tend to guess "obvious", easy words that provide less informative information for labeling. Related works have been done to encourage variety, such as _Taboo Words_, and _Dynamic Scores_. 

We looked to address this issue from a different path. Inspired by the work about _Human In the Loop for visual recognition_, we thought by bringing domain knowledge structure, human participants behavior shall be guided to not that easy-guess-by-participant, but more preferred-by-host results. In our project, we specifically **incorporated predefined categorizations levels of labels, into the basic setting of a ESP game**, 

![Yogurt screenshot]({{ "/assets/project_img/happylabel_tree.jpg" | absolute_url }})_The Predefined Category Tree_


This game consist of following features:

-   A predefined tree structure of   categories
-   Options are limited: shuffled in case of collusion.
-   Progressive guessing: feels like Who wants to be Millionaire
-   Dynamic score rewarding

![Yogurt screenshot]({{ "/assets/project_img/happylabel_interface.jpg" | absolute_url }})_The Game Interface_


The web client was built with Html/Css & jQuery, the server was written with node.js, and database was on firebase

Take a look at our live demo videos at Youtube:

<p><style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }</style><div class='embed-container'>    <iframe title="YouTube video player" width="640" height="390" src="http://www.youtube.com/embed/35H1t3_qbSg" frameborder="0" allowfullscreen></iframe></div>
 <p><img></img><em>Watch How it Plays in Video</em></p>

<br>
To evaluate the efficiency and accuracy of the image labeling with our design, we published HappyLabel online to collect data. And in addition, we conducted a user interview involving 5 players to evaluate the gameplay of HappyLabel. You can find the result in attached image.



 ![Yogurt screenshot]({{ "/assets/project_img/happylabel_testresult.jpg" | absolute_url }}) _Preliminary Test Result_



