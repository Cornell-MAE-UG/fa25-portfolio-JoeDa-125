---
layout: project
title: Torque Wrench Design and Analysis
description: Class project with Graphs
technologies: [MATLAB, ANSYS]
image: /assets/images/TorqueWrenchCover.png
---

<div style="float: top; margin-left: 15px;">
  <img src="{{ site.baseurl }}/assets/images/CAD_Model.jpeg" alt="CAD Photo" style="width: 350px">
</div>
 **Material Used:**
 - Ti-6Al-4V
 
 Material Properties:
 - $E = 17.3e3psi$
 - $\nu = 0.37$

The images below depeicts how laods and boundary conditions were applied to my fem model.

<div style="float: left; margin-left: 0px;">
  <img src="{{ site.baseurl }}/assets/images/
ANSYS_Loading.png" alt="ANSYS Photo" style="width: 600px">
</div>
Next is the FEM anlysis output of my normal strain in the gauge direction.
<div style="float: left; margin-left: 0px;">
  <img src="{{ site.baseurl }}/assets/images/
Normal_Strain.png" alt="ANSYS Photo 2" style="width: 
600px">
</div>
Next, I plotted the contours of the maximum principal stress found in my model.
<div style="float: left; margin-left: 0px;">
  <img src="{{ site.baseurl }}/assets/images/
MPrin_Stress.png" alt="ANSYS Photo 3" 
style="width: 
600px">
</div>
SUMMARIZE RESULTS BELOW

The torque wrench sensitivity in mV/V from my FEM anlysis was $1306.7\mu\epsilon$
<div style="float: left; margin-left: 0px;">
  <img src="{{ site.baseurl }}/assets/images/
Strain_Probe.png" alt="ANSYS Photo 4" 
style="width: 
600px">
</div>
