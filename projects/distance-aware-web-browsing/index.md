+++
title = "Distance Aware Web Browsing"
date = 2018-06-02T21:03:07-04:00
draft = true

tags = ["computer-vision"]

summary = "WebBrowser++ is a system that brings distance awareness to your web browser!"
+++
This project was done as my course project for CS889: Applied Computer Vision in Human-Computer Interaction at [the University of Waterloo](https://uwaterloo.ca/). 

I built a prototype system called WebBrowser++ for augmenting existing web browsing experience. WebBrowser++ estimates the distance between the user and the screen and performs zoom-in automatically as the user moves away from the screen to account for the shrinking of the on-screen content. If the distance between the user and the screen exceeds a predefined threshold, the system infers that the user is in a different state and switches to a different mode. The user can control the web browser via simple gestures from a distance. Currently, the system can recognize hand movements in four different directions (up, down, left and right).