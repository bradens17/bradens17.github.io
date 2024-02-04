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
I learned ALOT from this project. To start we used an MSP430 microcontroller chip. We soldered onto our own board which I had minimal experience with prior. After soldering on the chip 4 times, I got fairly good at soldering small components and was pretty familiar with the heat gun to remove parts. 

I also did all the firmware for this project. We used a stepper motor for yaw rotation and a servo motor for opening and closing the mouth. Additionally, we had the LED eyes to depict emotion and 3 limit switches for phone detection and for stopping the motor. All this control was done using the MSP430 using code composer. 

We also used computer vision to track the users movement and detect if they are on task. My partner led this part of the project and I assisted. 

The mechanical design was done using OnShape CAD and we 3D printed 95% of the parts. We decided to make it look like croc as it was cute and we wanted an animal with a big mouth that could "eat a phone". This required surface modelling to make the face look like a croc.

We made a huge mistake when desigining this... we had the idea of making this into a product and had product design in our heads. We only a 2-3 weeks to design and build this and we should have had the mindset of just building minimum viable product prototype just ensuring our main funcitons work. But we tried to make it as compact as possible, this led to alot of issues with wiring and on demo day we had a short that cause our board to break. (The other reason was because we didnt have any heat shrink or electrical so we may have had some open wires)

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/chassisprody.jpg" loading="lazy" alt="Project">
    <img src="/images/bottomprody.jpg" loading="lazy" alt="Project">
  </div>
  <em> <a href="https://unsplash.com/" target="_blank"></a></em>
</div>

We ended up redesigning to make the bottom section much more open as shown below. This allowed for our wires not to get caught on eachother and was much easier to assemble but still met all the requirements we wanted. We used purchased electrical tape to cover any exposed wires this time.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/bottomprodyV2.jpg" loading="lazy" alt="Project">
  </div>
  <em> <a href="https://unsplash.com/" target="_blank"></a></em>
</div>