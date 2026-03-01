---
layout: project
title: CFD Car Analysis
description: Performing fluid dynamical analysis on past car design
technologies: [ANSYS Fluent]
image: /assets/images/Pressure_Contour.png
---

This was an undertaking for my project team, Cornell Electric Vehicles, that saw me single-handedly learning how to use the ANSYS Fluent CFD software to conduct a thorough aerodynamic analysis of past car designs. I learned how to use the software from both online courses and in person guidence by Rajesh Bhaskaran, the director of Cornell's Swanson lab for simulations.

------

Below are some of the results from one of my successful simulations
<div style="float: left; margin-left: 0px; 
margin-bottom: 15px;">
  <img src="{{ site.baseurl }}/assets/images/
vsymmetrycontour1.png" alt="ANSYS Photo" 
style="width: 600px">
</div>
<br style="clear: both;">
Pictured above is a contour plot of the velocity around the axis of symmetry of our car. This plot has given my team valuable information regarding where the separation point for the flow is on the trailing end of the car. This data will help improve future designs by allowing us to more carefully control where the flow separates, greatly reducing our car's drag coefficient.
<div style="float: left; margin-left: 0px; 
margin-bottom: 15px;">
  <img src="{{ site.baseurl }}/assets/images/
Streamline1.png" alt="ANSYS Photo" 
style="width: 600px">
</div>
<br style="clear: both;">
This plot of streamlines over our car shows how the flow developes and what path it is likely to take over the vehicle. The curvature of the lines and how close they are together can also be used to infer the pressure and velocity distributions over the car. Areas of high pressure want to be avoided if posasible to minimize drag, so seeing these from the analysis can help us understand howe to better design the car without expensive wind tunnel testing,
<div style="float: left; margin-left: 0px; 
margin-bottom: 15px;">
  <img src="{{ site.baseurl }}/assets/images/
undercar1.png" alt="ANSYS Photo" 
style="width: 600px">
</div>
<br style="clear: both;">
In previous years our team had designed a baseplate in a manner that was meant to generate lift, thereby taking weight off unsprung components and decreasing rolling resistance. One of the most important finding of my analysis was that this effect was **not working** as we would have liked, and that the geometry added more complexity that outweighed the benefits of the added lift. It was therefore decided after this analysis that our team will switch back to a flat base plate, a decision helped by the findings from my analyis

------

If you would like to review my more in depth presentation on my research, you can view the following slideshow <a href="{{ '/assets/Joe_CFD_Presentation.pdf' | relative_url }}">here</a>