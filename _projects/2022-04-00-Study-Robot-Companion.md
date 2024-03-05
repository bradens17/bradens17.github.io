---
title: Study Robot Companion
date: 2023-04-01 08:01:35 +0300
subtitle: Mechatronics, Firmware, Computer Vision
image: '/images/normal.jpeg'
---

# The Challenge
Many students including me have difficulties staying focused while studying. People often have study buddies to help them stay on task. In this project a design a robot study companion that helps you stay on task, and specifically staying off your phone. 

# Explainer Video
<p><iframe src="https://player.vimeo.com/video/909578755?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" loading="lazy" width="640" height="360" frameborder="0" allowfullscreen></iframe></p>

# What I learned
I gained extensive knowledge through this project, starting with the utilization of an MSP430 microcontroller chip. The hands-on experience of soldering onto our custom board, despite my limited prior exposure, enabled me to develop proficiency after soldering the chip four times. I became adept at handling small components and familiar with using a heat gun for part removal.

## Firmware
Additionally, I took charge of the firmware development for the project. We incorporated a stepper motor for yaw rotation, a servo motor for the mouth's opening and closing, LED eyes to convey emotions, and three limit switches for phone detection and motor cessation. All these controls were orchestrated using the MSP430 and Code Composer.

## Computer Vision
Incorporating computer vision for user movement tracking and task detection was another facet of our project. My partner led this segment, and I provided assistance.

## Mechanical Design
The mechanical design was executed through OnShape CAD, and 95% of the components were 3D printed. We opted for a crocodile-inspired design for its cuteness and the symbolic concept of "eating" a phone, necessitating surface modeling for the crocodile face.

In the image to the right, you can observe the slew bearing that I meticulously designed and 3D printed. By purchasing a pack of small steel balls and 3D printing the remaining four sections, I successfully assembled my personalized slew bearing for a mere $25. This stands in stark contrast to the exorbitant cost of over $1000 for a similar-sized engineered steel bearing.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/chassisprody.jpg" loading="lazy" alt="Project">
    <img src="/images/bottomprody.jpg" loading="lazy" alt="Project">
  </div>
  <em> <a href="https://unsplash.com/" target="_blank"></a></em>
</div>

## Failure
A critical lesson emerged during the design phase. Although we initially envisioned turning the project into a product, we had a limited timeframe of 2-3 weeks for both design and construction. Instead of adopting a mindset focused on building a minimum viable product prototype, we attempted to make it as compact as possible. Unfortunately, this decision led to wiring issues, and on demo day, a short circuit occurred, causing our board to malfunction. Lack of heat shrink and electrical tools may have contributed to open wires exacerbating the situation.

Upon reflection, we decided to refine the design by significantly increasing the openness of the bottom section, as illustrated below. This modification not only prevented our wires from getting entangled but also simplified the assembly process, meeting all our specified requirements. To secure and protect the exposed wires, we opted for purchased electrical tape in this iteration.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/bottomprodyV2.jpg" loading="lazy" alt="Project">
  </div>
  <em> <a href="https://unsplash.com/" target="_blank"></a></em>
</div>