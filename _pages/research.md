---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<!-- <style> -->
<!-- iframe { -->
<!--   height: 100%; -->
<!--   width: 175px !important; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   width: 175px; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   border: 1px solid red; -->
<!-- } -->
<!-- .col-md-3 { -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   overflow:hidden; -->
<!--   display: table-cell; -->
<!--   text-align:center; -->
<!--   background: white; -->
<!--   width: 175px; -->
<!--   border: 0px solid transparent; -->
<!--   border-radius:20px; -->
<!-- } -->
<!-- </style> -->

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
  <!-- border: 1px solid black; -->
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

  <!-- border: 5px solid red; -->
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- float: none; -->

## Research strategy

My research strategy consists of a virtuous cycle to 
<i>understand</i>, <i>model</i>, and <i>manipulate</i>
multi-component/-phase flows using high-fidelity 
numerical methods and theory in collaboration with 
experiments. I advance the ability to numerical compute 
these flows with high-order accurate, 
interface-capturing Eulerian (flow-focused) methods. 
The intent of such computations is two-fold. First, 
simplified-physics models are developed from these 
simulations to predict the flow behavior in certain 
environments and/or conditions. Second, these lower-order 
models are used to simulate experiments and/or operating conditions.

## Research thrusts

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Spherical bubble dynamics near soft materials</h4>
The manipulation of cavitating, bubbly flows is a critical 
to prevent or enhance deleterious effects in naval hydraulic, 
energy science, and biomedical applications. I have developed
numerical methods to <i>understand</i> and <i>model</i> spherical 
* I have collaborated with experimental researchers to study <a href="{{ site.url }}{{ site.baseurl }}/papers/wilson-pre-19.pdf" target="_blank">laser- and ultrasound-generated spherical bubbles</a>
* Studied spherical, single bubble dynamics in viscoelastic environments pertinent to<a href="{{ site.url }}{{ site.baseurl }}/papers/mancia-pmb-19.pdf" target="_blank">modeling tissue damage</a> and <a href="{{ site.url }}{{ site.baseurl }}/papers/mancia-pmb-20.pdf" target="_blank">ultrasound wave form</a> in biomedical applications
* I am a developer of the open-source solver <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-cav-21.pdf" target="_blank">MFC</a>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Non-spherical bubble dynamics near deformable materials</h4>
The manipulation of cavitating, bubbly flows is a critical 
to prevent or enhance deleterious effects in naval hydraulic, 
energy science, and biomedical applications. I have developed
numerical methods to <i>understand</i> and <i>model</i> these 
flows. 
* I have developed an <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-JCP-19.pdf" target="_blank">Euleriean, high-order accurate interface-capturing model</a>
that accounts for gas, liquids and solids
* Applied the model to the Advected Upstream Method (AUSM) approach to study <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-shockwaves-19.pdf" target="_blank">shock-viscoelastic droplet interactions</a>
* Studied spherical, single bubble dynamics in viscoelastic environments pertinent to<a href="{{ site.url }}{{ site.baseurl }}/papers/mancia-pmb-19.pdf" target="_blank">modeling tissue damage</a> and <a href="{{ site.url }}{{ site.baseurl }}/papers/mancia-pmb-20.pdf" target="_blank">ultrasound wave form</a> in biomedical applications
* I am a developer of the open-source solver <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-cav-21.pdf" target="_blank">MFC</a>

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/455888052?autoplay=1&loop=1&autopause=0&muted=1&quality=240p&background=1" height="182px" frameborder="0" allow="autoplay"></iframe>
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">

<h4>Flow-induced, high-strain-rate material deformations</h4>
In extreme conditions, fluid flow induces high-strain-rate 
deformations of materials. These materials can vary in mechanical 
properties and stress response from biological (soft, low stress) 
tissues to metals with high strength (hard, high stress). 
I create high-fidelity computational methods to simulate these 
dynamics in a monolithic Eulerian framework.
Examples are:
* Euler--Euler and Euler--Lagrange <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-19.pdf" target="_blank">sub-grid bubble cloud models</a>
* Accelerated models using a <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-20.pdf" target="_blank">statistical paradigm and neural networks</a>
* Implementation in my open-source solver <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-CPC-19.pdf" target="_blank">MFC</a>

These enable realistic simulation of the bubble populations that nucleate during treatment.
This has impacted application-specific treatments, including:
* Improved _burst-wave lithotripsy administration_ in human trials 
* Understanding of <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-JCP-20.pdf" target="_blank">bubble-collapse-rebound</a> dynamics
* Cavitation-induced <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-JFM-19.pdf" target="_blank">erosion potential</a> for rough materials
</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/455888052?autoplay=1&loop=1&autopause=0&muted=1&quality=240p&background=1" height="182px" frameborder="0" allow="autoplay"></iframe>
</div>
</div>
</div>

