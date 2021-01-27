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
environments and/or conditions. Second, these reduced-order 
models are used to simulate experiments and/or operating conditions.

## Research thrusts

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">

<h4>Flow-induced, high-strain-rate material deformations</h4>
In extreme conditions, fluid flow induces high-strain-rate 
deformations of materials. These materials can vary in mechanical 
properties and stress response from biological (soft, low stress) 
tissues to metals with high strength (hard, high stress). 
I develop high-fidelity computational methods to simulate these 
dynamics in an Eulerian framework.
* I have developed an <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-JCP-19.pdf" target="_blank">Eulerian, high-order accurate interface-capturing model</a>
that accounts for gas, liquids and viscoelastic solids
* Applied the model to the Advected Upstream Method (AUSM) approach to study <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-shockwaves-19.pdf" target="_blank">shock-viscoelastic droplet interactions</a>
* I applied this framework to study <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-thesis-18.pdf" target="_blank">cavitation bubble collapse near a compliant material</a>
</div>

<div class="col-md-3 col-sm-12" style="background-color:transparent;">
<video width="200px" height="200px" autoplay loop>
 <source src="{{site.url}}{{site.baseurl}}/images/videos/sic_layer.mp4" type="video/mp4">
</video>
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Spherical bubble dynamics in soft matter</h4>
The manipulation of cavitating, bubbly flows is a critical 
to prevent or enhance deleterious effects in naval hydraulic, 
energy science, and biomedical applications. In these applications
the bubble remains spherical and oscillates in volume in response
to its contents and the surrounding material forces. In this work: 
* I have collaborated with experimental researchers to study <a href="{{ site.url }}{{ site.baseurl }}/papers/wilson-PRE-19.pdf" target="_blank">laser- and ultrasound-generated spherical bubbles</a>
* Studied spherical, single bubble dynamics in viscoelastic environments pertinent to <a href="{{ site.url }}{{ site.baseurl }}/papers/mancia-pmb-19.pdf" target="_blank">modeling tissue damage</a> and <a href="{{ site.url }}{{ site.baseurl }}/papers/mancia-pmb-20.pdf" target="_blank">ultrasound wave form</a> in biomedical applications
* Studying the non-linear wave energy losses due to laser-induced cavitation bubbles
</div>
  <div class="col-md-3 col-sm-12" style="background-color:transparent">
   <p><img src="{{site.url}}{{site.baseurl}}/images/pubpic/pmb2019.png" width="175px" /></p>
   </div>
  </div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Non-spherical bubble/droplet dynamics near objects</h4>
The manipulation of cavitating, bubbly flows is a critical 
to prevent or enhance deleterious effects in naval hydraulic, 
energy science, and biomedical applications. Below are 
my contributions to this area:
* I studied the inertia-driven bubble collapse dynamics in a channel <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-JCP-19.pdf" target="_blank">to determine the effect of confinement</a>
* I developed a <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-JCP-19.pdf" target="_blank">potential flow model</a> to study asymmetric cylinder collapse for 3D Eulerian-Eulerian sub-grid bubble cloud models
* Implementation in my open-source solver MFC to <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-thesis-18.pdf" target="_blank">study cavitating bubbles underoing phase change</a>
</div>

<div class="col-md-3 col-sm-12" style="background-color:transparent;">
<video width="200px" height="200px" autoplay loop>
 <source src="{{site.url}}{{site.baseurl}}/images/videos/droplet_wall.mp4" type="video/mp4">
</video>
</div>
</div>
</div>



