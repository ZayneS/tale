---
title: "RAAS, a conceptual design of future automotive signal system"
layout: project
img_url: /assets/project_img/raas_thumb.jpg
description: We brought up an alternative interface design concept for car-to-car, or car-to-environment communication. .
date: "2013-6-10"
---


> _The final project for COMM269 Computers and Interfaces_

<br>

RAAS was a design project for [COMM269 Computers and Interfaces](http://web.stanford.edu/class/comm169/) taught by [Prof. Clifford Nass](https://en.wikipedia.org/wiki/Clifford_Nass). It was worked together with [Ningxia Zhang](http://ningxiazhang.com/).

In this project, we brought up an alternative interface design concept for Car2Car, or Car2Environment communication. 

<br>

## Show respect to car's safety zone 

**Challenges: how to avoid accidents due to lack of safe distance and abusive of road rights?**

![RAAS ]({{ "/assets/project_img/raas_roadright.png" | absolute_url }})_Abusive of road rights, Image from DMV California_


Current OEM and suppliers in automotive industry are working very hard to solve this problem, specifically with the development of _Active Driver-Assistance Systems (ADAS)_ .

Features like _Collision Avoidance_, _Adaptive Cruise Control_ use sensors to capture behaviors and intensions of cars around the driver’s car, and take actions in response. It is, however, a passive, one-way, “guess-and-react” approach, and thus the delay in reaction shall always exist. 

It has been shown that, in many business of lives, an active, two-way communication is more efficient for reaching consensus and conducting responsive activities. 

Thus, a new challenge arises: **Can we facilitate a two-way communication between driver’s car and cars around regarding safe distances and road rights, or in other sense the safety zone?** 

In this project, we have tried to find an innovative and low-cost approach to address this challenge.

<br>

## Related designs about active communication

Current vehicles are mounted with onboard signal devices, such as turn indicators, break lights etc. These signals allows others to see a vehicle’s presence, speed and travel direction, as well as drivers intentions regarding direction and speed changes.

![RAAS ]({{ "/assets/project_img/raas_tail_signals.png" | absolute_url }})_Tail indicators and signals, Image from DMV California_

At the same time, more and more cyclists are using with Laser light to beam their road rights out from blind spots of cars and other road occupants.


![RAAS ]({{ "/assets/project_img/raas_inspiration_2.jpg" | absolute_url }})_Laser to beam out road rights, Image from Beryl_

![RAAS ]({{ "/assets/project_img/raas_inspiration_3.jpg" | absolute_url }})_Laser to beam out safety zone of a cyclist, Image from xfireshop_

<br>

## To highlight the safety zone actively

Inspired by the mounted signals and laser lights. We brought out the concept of **Range Awareness Assistant System (RAAS)**. 

RAAS uses laser beams to project the predictive trajectory of the car on the ground in front of it, based on the car’s current velocity and trie tractions. The length of project area demonstrated the estimated braking distance at current speed.

A driver may use RAAS to show the safety zone of his car. On one hand it works as a reminder for driver to keep safe distance for emerging braking, on the other, it declares the road right and warn other cars from driving into and causing collision. 

![RAAS ]({{ "/assets/project_img/raas_1.jpg" | absolute_url }})
![RAAS ]({{ "/assets/project_img/raas_2.jpg" | absolute_url }})

<br>


## To express a driver’s intension

Given that safety zone is dynamic according to changes of a driver’s behavior, RAAS can work as a good media to better express a driver’s intension to change.

RAAS's laser beams can change projecting direction, so that the projected laser marking on road can alter spread area and shape to better illustrate driver’s intension.

![RAAS ]({{ "/assets/project_img/raas_3.jpg" | absolute_url }})
![RAAS ]({{ "/assets/project_img/raas_4.jpg" | absolute_url }})
![RAAS ]({{ "/assets/project_img/raas_5.jpg" | absolute_url }})