---
layout: free
permalink: /toys
title: "Code & Toys"
subtitle: ""
description: "Experiments with hardware and software. "
type: "case-study"
year: "2015"
img: "codeart.png"
banner: "group.png"
case-study: true
hide: false
action: "Take a Look"
special: "codeart"
---
<script type="text/javascript" src="/assets/js/processing.min.js"></script>
<script type="text/paperscript" src="/assets/js/needlesClickable.js" canvas="canvasThumbnail"></script>
<script src="https://d3js.org/d3.v3.min.js" charset="utf-8"></script>
<script type="text/paperscript" src="{{site.baseurl}}/assets/js/medium.js" canvas="canvasMedium"></script>

<section id="intro" class="cf mb4 w-100 mt4">
  <header class="fn fl-l w-50-l w-100">
      <h1 class="f-headline-l f-subheadline-m f1 fw4 lh-solid baskerville mt0">Code & Toys</h1>
    </header>
    <div class="fn fl-l w-50-l w-100"><p class="mt0-ns lh-copy">Experiments with hardware and software.</p></div>
</section>
<section>
    <canvas resize="true" id="canvasThumbnail" style="background:#ea5a41"></canvas>
    <p class="f4 fw4 mt4 graphik">Needles <span class="black-30">2015</span> <span class="fw4">simulating a magnetic field. Click to reset magnet.</span></p>
</section>
<section id="starfield" class="cf mv6 bb--black">
  <div class="cf">
    <div class="fn fl-l w-50-l cover pr4-l mb3 mb0-ns">
      <img src="{{site.baseurl}}/assets/img/starfield/a1.gif" width="100%" class="mb3">
    </div>
    <div class="fn fl-l w-25-l pr4-l ">
        <img src="{{site.baseurl}}/assets/img/starfield/maps.png" class="mb3 " width="100%">
        <img src="{{site.baseurl}}/assets/img/starfield/a4.gif" width="100%">
    </div>
    <div class="fn fl-l w-25-l cover">
        <p class="lh-copy mt0-ns mt4">
          Starfield 
          <span class="black-30">2015</span> 
          <span>pseudo random terrain maps</span>
        </p>
    </div>
  </div>  
</section>
<section id="invaders" class="cf mv6 bb--black">
  <div class="cf"><canvas data-processing-sources="{{ site.baseurl }}/assets/spaceinvaders/spaceinvaders.pde"></canvas></div>
  <p class="mt4 lh-copy">
    Invaders <span class="black-30">2016</span>
    <span>Randomly generated invaders inspired by <a href="http://www.complexification.net/gallery/" class="black underline">Jared Tarbell.</a> Try clicking!</span>
  </p>
</section>
<section id="snake" class="cf mv5 bb--black">
  <div class="embed-container">
  <iframe src="https://player.vimeo.com/video/282559899?background=0"   class="" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  </div>
  <p class="mt4 lh-copy">
    Snake3D 
    <span class="black-30">2016</span> 
    <span class="fw4">The nokia classic now in an extra dimension.</span>
  </p>
</section>
<section>
    <div class="medium">
      <canvas resize="true" id="canvasMedium" style="background:#000"></canvas>
    </div>
    <p class="mt4 lh-copy">
      Medium 
      <span class="black-30">2017</span>
      <span>Identity for <a class="black link underline" href="https://cornellmedium.design/">Medium, a design collective</a> I got going with friends at university.</span>
    </p>
</section>
<div class="mt6 mb5">
<a href="{{site.baseurl}}/" class="f4 link dark-red">Go home</a>

</div>


