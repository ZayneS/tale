---
title: "Car Styling Design Preference Prediction with Machine Learning"
layout: project
img_url: /assets/project_img/CarPrefer_thumb.jpg
description: How (much) can we facilitate the product design process with customer preference data?
date: "2012-4-13"
---


> _It was the final project for EECS 545 Machine Learning at U of Michigan_


<br>
##Can we facilitate faster design process with A.I.?

Due to increased competitions in automotive industry, car designers & engineers are facing challenges of compressed lead time for development and costly risks in design innovations. 

Can we bit the challenge with more efficient design process with faster product-market-fit decisions? We intended to find the possibility with data of previous customer purchasing behaviors, and the assistance of machine learning.

<br>
##Ranking Support Matrix Machine for Vehicle Face Prediction


### Problem Definition

1. To enable more efficient and effective design decisions
2. We intended to realize automated design inspiration based on user preference modeling.


We limited the problem space to car frontal face design. and studied the relationship between the demographics of an individual, and the geo-metric shape of the vehicle face.

![Placeholder image]({{ "/assets/project_img/CarPrefer_1.jpg" | absolute_url }})


### Strategies

![Placeholder image]({{ "/assets/project_img/CarPrefer_2.jpg" | absolute_url }})


### Methods & Algorithms

* Demographic & Preference record classification: Bilinear ranking SVM methods for preference classification.

<img class="math-expression" src="/assets/project_img/CarPrefer_7.png" alt=""></img>

* Feature extraction: Edge detection methods.

![Placeholder image]({{ "/assets/project_img/CarPrefer_6.jpg" | absolute_url }})


* New buyer’s design preference prediction: Linear regression.

![Placeholder image]({{ "/assets/project_img/CarPrefer_4.jpg" | absolute_url }})


### Test results

1. Bilinear ranking SVM is a good tool for preference prediction;
2. Edge detection methods was not powerful enough to extract models that can represent car’s aesthetic features for this study.
3. Preference prediction result lacks fidelity for design prediction.

It was the final project for EECS545 Machine Learning. It was done with Alex, Hareen and Yiying. you can find the final report here.
[Ranking Support Matrix Machine for Vehicle Face Prediction](https://www.dropbox.com/s/ci3gtvnqnju323t/EECS545_Burnap_Kancharla_Shen_Zhu_Final_Report.pdf?dl=0)

<br>
## Challenges, learnings and unsolved problems

### a. A decision space is not a design space

Ranking decisions can be linear and discrete when we assign sequential numbers to choices. however, different designs for these choices are, in most cases, not. 

When using RVMM, the model was trained to represent the mapping from demographic space to a linear ranking decision space. The prediction was also a linear combination of existing choices. The problem was that a (3.5 SUV_01 + 0.5 Sedan_03) did not always make sense for actual design prediction since designers cannot interpret this choice in actual design parameters. It was impossible for us to map such combination back to the original design spaces.

In the end, we found RVMM was a good algorithm to recommend choices that were already existed. We got very good result when running it in movie recommendation tests. But it failed to predict things that were not exist, and thus failed for design recommendations.

<br>
### b. Finding the valuable features

Another major challenge in this research was to find the useful features regarding car designs and that are actually affect customers' decisions. 

we focus on discovering features that deliver the greatest predictive power with the lowest computational overhead.

During the project, choosing the subset of headlight was the wrong direction after we found features of the entire front face of the car was too difficult to extract. In fact, styling is just one aspect for people’s purchasing considerations, more are about performances, fuel-efficiency , spaces, and of course prices.

<br>
## Future directions and related works

Future studies to address challenges in two directions we just discussed about have been conducted by Alex Burnap in his Ph.D. researches. You can find related reports and publications at 
<a href="http://www.aburnap.com/" target="blank">www.aburnap.com</a>



