---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<style>
code {padding: 6px 8px; font-size: 90%;}
</style>

# Welcome!

<br/>
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
 
<br/>

<div class="row" style="text-align:center">
<video controls autoplay muted loop width="90%" style="display:inline-block; border-radius: 25px; border:0px solid #FFF;">
  <source src="{{ site.url }}{{ site.baseurl }}/images/videos/3dtrain_breakdown2.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
  Breakdown of a flowing cell train. Bryngelson & Freund, *Phys. Rev. Fluids* (2018)
</div>
<br/>

#### `about me`

I am a Postdoctoral Scholar Research Associate at the <a href="https://www.caltech.edu/" target="_blank">California Institute of Technology</a>, working with <a href="https://www.colonius.caltech.edu/" target="_blank">Professor Tim Colonius</a>.
I have a Ph.D. and M.S. in <a href="https://mechanical.illinois.edu/graduate/graduate-degree-programs/phd-programs/phd-theoretical-and-applied-mechanics" target="_blank">Theoretical and Applied Mechanics</a> from the University of Illinois at Urbana–Champaign (2017 and 2015), where I worked with <a href="https://aerospace.illinois.edu/directory/profile/jbfreund" target="_blank">Professor Jonathan Freund</a>.
I hold a Bachelors in Mechanical Science and Engineering from the University of Illinois at Urbana-Champaign (2010).

<br/>
<div class="well-md">
<h3>Sponsors</h3>
<div style='display:block; text-align:center; margin-left:auto; margin-right:auto;'>
 {% for funder in site.data.funders %}{% if funder.url %}<a href="{{funder.url}}" target="_blank"><img src='/images/logopic/{{ funder.image }}' style='max-height: 70px; max-width: 170px;'/></a>{% else %}<img src='/images/logopic/{{ funder.image }}' class='mycenter' style='max-height: 70px; max-width: 170px;'/>{% endif %}   {% endfor %}
</div>

</div>


