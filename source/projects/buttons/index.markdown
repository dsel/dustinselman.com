---
layout: page
title: "Button Box"
date: 2013-05-13 18:30
comments: true
sharing: true
footer: true
---
I found a source for cheap arcade buttons and went on a kick of adding them to everything I could. I started by slapping this box together with and arduino and bluetooth module I picked up from [sparkfun](https://www.sparkfun.com/)<br>
The first thing I used it for was to control itunes playlists on my music server. Each button sent a control character of a serial connection to the server via the bluetooth module. A script living on the server triggered the appropriate applscript actions. <br>

{% img right /images/buttons_1.jpg 200  %}

Features:
<ul>
  <li>arduino</li>
  <li>bluetooth</li>
  <li>battery powered</li>
  <li>arcade buttons that can be arbitrarily mapped to various script actions</li>
</ul>

{% img /images/buttons_2.jpg 200  %}

Todo:
<ul>
  <li>easier access for battery replacement</li>
  <li>battery save mode and/or power switch</li>
  <li>convert to sending osc messages</li>
  <li>publish code to github</li>
</ul>
