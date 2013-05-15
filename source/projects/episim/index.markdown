---
layout: page
title: "Epidemic Simulator"
date: 2013-05-14 16:30
comments: true
sharing: true
footer: true
---
{% img right /images/episim_2.png 300  %}
Interactive epidemic simulator developed for an epidemiology course at Stanford.<br>
[episim.dustinselman.com](http://episim.dustinselman.com)



Features:

* written in [Processing](http://www.processing.org)
* uses the [controlP5](http://www.sojamo.de/libraries/controlP5/) library for all ui elements
* three real time visulaizations of [SIR model](http://en.wikipedia.org/wiki/Epidemic_model#The_SIR_Model) stats
* randomized organic movement using [Perlin noise](http://en.wikipedia.org/wiki/Perlin_noise)
* semi permeable barriers to partition the population
* real time interactive control of model variables
* data export of stats from current run


Todo:

* port to processing.js
* use [dat.GUI](http://workshop.chromeexperiments.com/examples/gui/#1--Basic-Usage) for ui elements
* allow recovered individuals to become susceptible again
* mortality rate
* birth

link: [episim.dustinselman.com](http://episim.dustinselman.com)<br>
code: [github.com/dsel/EpiSim](https://github.com/dsel/EpiSim)