---
layout: project
type: project
image: images/start.png
title: Slot Machine
permalink: projects/slot-machine
# All dates must be YYYY-MM-DD format!
date: 2018-11-01
labels:
  - Java
  - Games
summary: For my ICS 111 final project, I programmed an interactive slot machine simulation.
---

<img class="ui image" src="../images/slot.gif">
               *Note this is a GIF*

## INTRODUCTION:
Thisa was a project I had a lot of fun in thinking up, designing, and ultimately programming in my first Computer Science class. It is a simple and straightforward slot machine coded in [Java]({{ site.baseurl }}/projects/slot.txt). Users start off with an alloted amount of coins, which value gets added or subtracted to based on what combination of fruits they roll. I thought my project was unique, especially when compared to my peers', because instead of implementing fighting or shooting type games like the majority of students, I designed something more pattern/application-based.

## HOW DOES IT WORK?
The main coding framework behind this is known as the *finite state machine*. A finite state machine is a very simple, yet very effective coding techinque that is applicable in Computer Science as well as Engineering. Here, I designated the various "states" of my slot machine as the different logical steps one would take in interacting with the machine in real life. For example: starting the machine, spinning the rolls, obtaining coins, etc. Between the start and end states, nothing is static, and can be interchanged indefinitely until a user runs out of coins to play.

An "aha-moment" that I had when working on this project occured after the semester. When I submitted this project for grading, it actually was not implemented as a finite state machine. Instead, it was a messy entanglement of various objects and methods, that when put together, somehow managed to create a working slot machine. As you can imagine, coding this project was very frustrating and took a lot of trial-and-error.

After the semester had concluded, I revisted this project on my free time, and cconverted it to the finite state machine. It was beautiful how the code was now working in the same way, but also so smoothly and logically (and with much fewer lines of code). It was a breakthrough moment that made me appreciate the elegancy that code has the potential to achieve.

## TIME COMPLEXITY?
I thought it would be interesting to comment on the [time-complexity](https://www.happycoders.eu/algorithms/big-o-notation-time-complexity/) of this slot machine implementation. This slot machine is evaluated as having a time complexity of *O(1)* - or constant time. If you check the code you can see there are no for-loop iterations which would change the Big O evaluation. 

This also ties into the previous **HOW DOES IT WORK?** section. I mentioned how I initially programmed the slot machine in a chaotic, messy manner (I can't remember the exact code but I recall there was the use of for loops) before redoing it as a finite state machine. The finite state version can be seen as a better implementation of the slot machine in terms of code performance, because it does not use for loops which would change the time complexity to at least *O(n)*. In other words, the finite state machine version of the slot machine is more efficient than other slot machines that may have code that changes the Big O evaluation.

## CONCLUDING:
This fun project taught me the power of certain coding techniques. The idea that there is a lot more to a project underneath the graphics code-wise was also enforced. It also gave me more experience with working through the different stages of development of a project: going from a simple idea to an actual working device/software/etc. I look forward to programming something similar in the future!

***************************************************************************************

*This project was developed in the [Eclipse IDE](https://www.eclipse.org/) and utilized the [EZ Graphics Library](http://www2.hawaii.edu/~dylank/ics111/) created by graduate student Dylan Kobayashi.*


<!-- <img class="ui image" src="../images/hansel_uns_gretel.jpgg"> -->
