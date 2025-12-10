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
 The material that was chosen was Ti-6Al-4V. This was picked for its light weight and high yield strength. It has a relatively high Young's modulus, and was determined by my MATLAB script to meet all the requirements of the design.
 
**Material Properties:**
 - $E = 17.3e3 psi$
 - $\nu = 0.37$

The images below depeicts how laods and boundary conditions were applied to my FEM model.

<div style="float: left; margin-left: 0px; margin-bottom: 15px;">
  <img src="{{ site.baseurl }}/assets/images/
ANSYS_Loading.png" alt="ANSYS Photo" style="width: 600px">
</div>
<br style="clear: both;">
Next is the FEM anlysis output of my normal strain in the gauge direction.
<div style="float: left; margin-left: 0px;margin-bottom: 15px;">
  <img src="{{ site.baseurl }}/assets/images/
Normal_Strain.png" alt="ANSYS Photo 2" style="width: 
600px">
</div>
<br style="clear: both;">

Next, I plotted the contours of the maximum principal stress found in my model.
<div style="float: left; margin-left: 0px;margin-bottom: 15px;">
  <img src="{{ site.baseurl }}/assets/images/
MPrin_Stress.png" alt="ANSYS Photo 3" 
style="width: 
600px">
</div>
<br style="clear: both;">

**Below is a summary of my results from my FEM analysis:**
- Maximum normal stress: $41884 psi$
- Load point deflection: $0.29028in$
- Strain at strain gauge location: $0.0013067\frac{in}{in}$


The torque wrench sensitivity in mV/V from my FEM anlysis was $1306.7\mu\epsilon$
<div style="float: left; margin-left: 0px;margin-bottom: 15px;">
  <img src="{{ site.baseurl }}/assets/images/
Strain_Probe.png" alt="ANSYS Photo 4" 
style="width: 
600px">
</div>
<br style="clear: both;">
Finally, the strain gauge I selected for this wrench is the Omega SGD-2/350-LY13. It has dimensions of $2 mm x 2.5 mm$ which converts to $0.0787 in x 0.0984 in$, meaning there is plenty of room for it to fit on the design.