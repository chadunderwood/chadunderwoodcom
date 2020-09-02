---
layout: post
title:  How To Create Rounded Corner Divs
categories: til
tags: divs, css
excerpt_separator: <!--more-->
sitemap:
  lastmod: 
  priority: 
  changefreq: 'monthly'
  exclude: 'no'
---
I created a launcher to link to certain things from my social media. This will allow me included links to multiple things from the bios in my social media. I started with squared corner divs and decided I wanted something that looked a little more like a button. I am sure this is something I will need to use in the future a lot.
  
The border radius property in CSS is what allows you to round the corners on a square div. The lower, the number, the less round the corners are. The higher, the number, the more rounded the corners will get.

Only the border-radius property, in the example below, affects the roundness of the corners. This allow you to set the amount the corners will be rounded.

---  
#### EXAMPLE CODE  
 	<code>
    <style>
    .example {  
    width: 100px; 
    height: 40px;
    background-color: black;
    border-radius: 15px; 
    }
    </style>
    <div id="example">
    </div>
#### OUTPUT
<div id="example" style="width: 100px; height: 40px; border-radius: 15px;background-color: black;"><div>

