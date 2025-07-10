---
layout: page
title: Personal projects
permalink: /projects/
---
## Ongoing projects:

### Software-Developer at [FasTTUBE](fasttube.de)
At the FormulA STudent Team TU-BErlin, we prepare for and then participate in the yearly formula-student events
hosted all over europe with an electric race car that is designed and build from scratch - every year - by over 80 students
from programs and universities all over berlin. As we don't just compete in the manual, but also autonomous divisions, this not only
poses challenges in mechanical- and electrical engineerings, but also at the intersection of machine learning software, robotics
and hardware integration.

Personally, I started at the beginning of this season (WiSe 2024/25) in the software-team as I was looking to apply my knowledge 
and sharpen my robotics-skills after my start as a full-time student. I felt that this was not only a fun way to engage 
in interdisciplinary work, but also something I could learn a lot from.

Thus, over this season, I was able to deeply sink into the forefront of how to make autonomous race-car driving work
on limited hardware capabilities. Starting with a complete hardware change and a team comprised of only new members, we had 
to adapt to and completely overhaul the technically very good (parts of it actually being used in teams all over europe, I discovered at this years [ARWO](https://arwo.hamburg/)!), though underdocumented code-base that was left by a team of highly-experienced coders from the last seasons.

This forced us to take a deep-dive into gsteamer, which we use to efficiently perform object detection from our two cameras, as well as 
ROS2, which connects the various parts of our code base. As the former is still under active development, this meant sorting through large C++ files and writing our own plugins to support our need to process camera input at a high frequency on our limited Intel-NUC hardware.

Furthermore, it also meant communicating with other parts of our team about the electronics powering our hardware, the integration and calibration of the steering equipment as well as the technical features the ever-evolving car design influenced on our cameras. Thus, it was essential to always improve ones' communication skills and team-work.
