---
layout: page
title: Cavitation
description: Co-simulation development for improved cavitation predictions in oil-hydraulic systems
img: assets/img/masters_cavitation/cavitation_6.png
importance: 2
category: masters
giscus_comments: false
---

Cavitation is a severe issue in hydraulic systems; triggering unwanted vibrations, degrading system efficiency, and causing catastrophic structural damage over time. 



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/masters_cavitation/cavitation_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/masters_cavitation/cavitation_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/masters_cavitation/cavitation_3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/masters_cavitation/cavitation_4.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Visualization of cavitation damage on hydraulic mining equipment manufactured by Epiroc AB. Components from two distinct, severely impacted locations are showcased, with green arrows pointing to regions of structural damage caused by the phenomenon. The blue circle highlights the undamaged cross-sectional outline of the pipe for comparison.
</div>

During my masters studies at Linköping University, I was involved in an industrial collaborative project with Epiroc AB to develop multi-scale methods to capture complex cavitation flows inside aging oil-hydraulic systems.

**Team members:** Twan Bakker, Rahul Gudur Suresh, and Aryan Delir

**University supervisors (Linköping University):** Marcus Jansson and Magnus Andersson

**Industry supervisors (Epiroc AB):** Maria Pettersson and Anders Olson

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/masters_cavitation/cavitation_5.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Co-simulation framework for communicating Hopsan and ANSY Fluent targeting improved numerical predictions for water hammer induced cavitation.
</div>

**Key Highlights &amp; Methodology**

<div class="project-highlights">
  <ul>
    <li>
      <strong>Co-Simulation Architecture:</strong> Improvements to a coupled simulation framework combining Hopsan (an open-source hydraulic system simulation tool developed at Linköping University) and ANSYS Fluent.
    </li>
    <li>
      <strong>Experimental Validation:</strong> Validated numerical predictions against experimental pressure measurements collected at three key points along a physical test-rig equipped with a transparent plexiglass tube for visual vapor-formation verification.
    </li>
    <li>
      <strong>Orifice &amp; Flow Analysis:</strong> Evaluated system behavior across four different orifice geometries (2 mm, 3 mm, and 5 mm diameters), achieving strong correlation between numerical model predictions and experimental benchmark data.
    </li>
    <li>
      <strong>Transient &amp; Water Hammer Dynamics:</strong> Analyzed complex cavitating flow behaviors caused by repetitive water hammer phenomena, evaluating how different valve movement profiles and the presence (or absence) of transient vapor bubbles influence pressure distribution during oil recirculation.
    </li>
  </ul>
</div>

This work is published as a <a href='https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1651071&dswid=8394'>technical report</a>, and was presented at Svenska Mekanikdagar at Luleå University of Technology (15–16 of June, 2022).