---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

## Welcome!

#### `research strategy`

My research strategy is to numerically compute flow physics to 
understand, model, and manipulate flows. By advancing numerical 
techniques with high-order accurate, interface-capturing Eulerian 
(flow-focused) methods, we can reliably understand these flows. 
The intention of such computations is two-fold. First, simplified-physics 
models are developed from these simulations to predict the flow behavior. 
These models are then used in computations simulating experiments or 
operating conditions. Second, quantify the uncertainty in both the 
simulations and experiments. This cycle continues and converging towards 
flow control.

<div class="container">
<div class="row">
<center>
<iframe src="https://player.vimeo.com/video/455688517?autoplay=1&loop=1&autopause=0&muted=1&quality=360p&background=1" width="100%" style="border-style:solid;border-radius:5px;" frameborder="0" allow="autoplay"></iframe>
Transition to chaos of flowing red blood cells. <br/>
Bryngelson & Freund, <i>Phys. Rev. Fluids</i> (2018)
</center>
</div>
</div>
<br/>

#### `about me`

I am a Postdoctoral Scholar Research Associate at the <a href="https://www.caltech.edu/" target="_blank">California Institute of Technology</a>, working with <a href="https://www.colonius.caltech.edu/" target="_blank">Professor Tim Colonius</a>.
I have a Ph.D. in <a href="https://me.engin.umich.edu/" target="_blank">Mechanical Engineering</a> from the University of Michigan, Ann Arbor (2018), supervised by <a href="https://me.engin.umich.edu/people/faculty/eric-johnsen" target="_blank">Professor Eric Johnsen</a>.
I earned a Masters in Mechanical Engineering from Stanford University (2012) a Bachelors in Mechanical Science and Engineering from the University of Illinois at Urbana-Champaign (2010).

<div class="jumbotron">
  <h4>Sponsors</h4>
  <div style='display:block; text-align:center; margin-left:auto; margin-right:auto;'>
 {% for funder in site.data.funders %}<a href="{{ funder.url }}" target="_blank"><img src='{{ site.url }}{{ site.baseurl }}/images/logopic/{{ funder.image }}' style='max-height: 80px; max-width: 200px; margin: 1%'/></a>{% endfor %}
  </div>
</div>
