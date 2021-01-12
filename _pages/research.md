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

My research strategy is to numerically compute these flow physics 
in a pragmatic fashion in collaboration with experiments. 
The approach consists of a virtuous cycle to 
<i>understand</i>, <i>model</i>, and <i>manipulate</i>
flows. By advancing our ability to numerical compute these flows 
with high-order accurate, interface-capturing Eulerian (flow-focused) 
methods I can reliably understand these flows. The intention of 
such computations is two-fold. First, simplified-physics models are 
developed from these simulations to predict the flow behavior 
in certain environments and/or conditions. Second, these models 
are then used in computations simulating experiments or operating 
conditions.

## Research thrusts

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Bubble dynamics in/near deformable materials</h4>
The manipulation of cavitating, bubbly flows is a critical 
to prevent or enhance deleterious effects in naval hydraulic, 
energy science, and biomedical applications. I have developed
numerical methods to <i>understand</i> and <i>model</i> these 
flows. 
* I have developed an <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-JCP-19.pdf" target="_blank">Euleriean, high-order accurate interface-capturing model</a>
that accounts for gas, liquids and solids
* Applied the model to the Advected Upstream Method (AUSM) approach to study <a href="{{ site.url }}{{ site.baseurl }}/papers/rodriguez-shockwaves-19.pdf" target="_blank">shock-viscoelastic droplet interaction</a>

TODO ADD a bullet with upcoming papers and Lauren's papers as well
* avitation erosion limits the operation life-cycle and performance 
of the Department of Energy's Spallation Neutron Source (SNS) experiments. 
* On the other hand, cavitation is desired in biomedicine applications. For 
example is non-invasive, focused ultrasound therapy tools. 
These tools generate cavitation bubbles to erode kidney and 
gallbladder stones (lithotripsy) or ablate soft, pathogenic 
tissues (histotripsy). Understanding the  
bubble dynamics and material response interactions is needed
to increase the efficacy of these tools.

Cavitating bubbles can ablate cancer cells, fragment tissues, and deliver drugs, among other functions.
I create high-fidelity computational methods to simulate these dynamics.
Examples are:
* Euler--Euler and Euler--Lagrange <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-19.pdf" target="_blank">sub-grid bubble cloud models</a>
* Accelerated models using a <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-20.pdf" target="_blank">statistical paradigm and neural networks</a>
* Implementation in my open-source solver <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-CPC-19.pdf" target="_blank">MFC</a>

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
Cavitating bubbles can ablate cancer cells, fragment tissues, and deliver drugs, among other functions.
I create high-fidelity computational methods to simulate these dynamics.
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

