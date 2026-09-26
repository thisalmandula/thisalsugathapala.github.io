---
layout: post
title: My Formula Student journey
date: 2023-07-31
description: A year with LiU Formula Student, designing and manufacturing the aerodynamic package of the ER22 Formula Student car.
tags: fluid-dynamics student-life hands-on
categories: engineering
thumbnail: assets/img/blog/fs1.webp
---

During my master's studies at Linköping University, I spent a year as a CFD Engineer with LiU Formula Student, working long nights developing the aero kit for the ER22 Formula Student car. It became one of those experiences I had dreamed about as a young engineering student in Sri Lanka. At my university back home, we had the ambition to build a Formula Student car and compete, but not the funding to make it a reality. Years later, I finally had the opportunity to join a large Formula Student team, made up not only of engineering students, but of students from different disciplines, working together almost like a real organization, with dedicated teams handling different aspects of the car's development.

My main responsibility was the design and optimization of the car's aerodynamic package, including the front and rear wings, diffuser, bargeboards, and side wings. We used full-car CFD simulations running on high-performance computing resources provided by the Swedish National Infrastructure for Computing (now called NAISS) at the National Supercomputer Centre (NSC) at Linköping University.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
           loading="eager"
           path="assets/img/blog/fs1.webp"
           class="img-fluid rounded z-depth-1"
           zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
           loading="eager"
           path="assets/img/blog/fs2.png"
           class="img-fluid rounded z-depth-1"
           zoomable=true %}
    </div>
</div>

<div class="caption">
    The ER22 Formula Student race car developed by LiU Formula Student
</div>

## Designing the aerodynamics

After joining the team, one of my first focuses was improving the overall CFD workflow. Our simulations involved several stages, from pre-processing in ANSA to mesh generation and simulations in ANSYS, followed by post-processing and visualization in ParaView. Since we needed to evaluate many different aerodynamic designs, running this entire process manually would have been extremely time-consuming. I therefore automated much of the simulation pipeline through scripting, reducing the amount of manual work required and allowing us to test and compare designs much more efficiently.

On the aerodynamic side, we used the simulations to study the pressure distribution across different components, identify and reduce regions of flow separation, and optimize the overall aerodynamic performance of the car. An important part of the process was also maintaining the desired aerodynamic balance, since improving the performance of an individual component was only useful if it worked together with the rest of the car.

Rather than looking at each component in isolation, we performed full-car CFD simulations. This allowed us to see how changes to one part of the aerodynamic package affected the flow reaching other components downstream, something that became particularly important when developing the front and rear wings, diffuser, bargeboards, and side wings.

<div class="row mt-3">
    <div class="col-md-6 mt-3 mt-md-0">
    <video
        class="img-fluid rounded z-depth-1"
        autoplay
        loop
        muted
        playsinline
        title="fs">
        <source src="{{ 'assets/img/blog/fs3.mp4' | relative_url }}" type="video/mp4">
    </video>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
           path="assets/img/blog/fs4.gif"
           class="img-fluid rounded z-depth-1"
           zoomable=true %}
    </div>
</div>

<div class="caption">
    full-car CFD simulations used during the aerodynamic development of ER22
</div>

## One piece at a time

One of my favourite parts of Formula Student was seeing the transition from numerical design to something physical. As someone who had spent much more time with books and simulations, I really wanted to gain more hands-on engineering experience. Piece by piece, we built the entire aero kit during the spring of 2022 using composite materials, particularly carbon fibre, at Etteplan and Marstrom Composites.

The manufacturing process itself was completely new to me. We first prepared moulds that defined the shape of each component and then carefully laid layers of carbon fibre over them. The layup was covered and vacuum-bagged, which helped compress the layers and remove trapped air, before being cured so that the resin hardened and the component took its final shape. After curing, the parts could be removed from the mould, trimmed, finished, and eventually assembled onto the car.

There was something especially satisfying about holding a component that had started out as a geometry on my computer screen.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
           loading="eager"
           path="assets/img/blog/fs5.gif"
           class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Manufacturing aerodynamic components for ER22 using composite materials
</div>

## Looking back

Formula Student gave me an early opportunity to apply my understanding of fluid dynamics to the design of aerodynamically efficient, full-car aero packages for Formula Student cars. It helped me further develop my understanding of road vehicle aerodynamics while also teaching me how to work within a large multidisciplinary team, where many different parts had to come together to solve complex, real-world engineering problems.

The experience also turned out to be valuable later in my PhD. In particular, the scripting skills I developed while automating post-processing in ParaView are still part of my workflow today. I now use many of those same skills to create visualizations of my direct numerical simulations (DNS). It is a nice connection between two very different problems: what started with visualizing airflow around a Formula Student car now helps me visualize turbulent flows and particle dynamics in my research.

For any student looking for something beyond lectures and coursework, I would definitely recommend joining a Formula Student team. You will probably spend more late nights than you expect, but the experience is worth it!

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid
           loading="eager"
           path="assets/img/blog/fs6.webp"
           class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    The aerodynamic unit of the ER22 Formula Student team
</div>