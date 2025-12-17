---
layout: project
title: Wind Turbine Blade Design
description: Advanced CAD Project
technologies: [Autodesk Fusion]
image: /assets/images/blade_cad.png
---

As part of a Heat and Fluids Lab course, a group of three other students and I were asked to design a wind turbine blade to optimize power output when operating at a fixed rotation rate. This gave us a chance to apply wind turbine concepts we learned throughout the semester such as modeling aerodynamic forces acting on the blades, modeling failure of the blades, obtaining and analyzing power curves, gathering data using LabVIEW instruments, and operating a wind tunnel.

While considering the constraints associated with this design challenge, our team conducted research on high performing wind turbine blades to help us determine an optimal blade length and airfoil. With some parameters solidified, we utilized blade element momentum theory to iterate over several potential blade designs. Through this process, we were able to calculate the expected performance of several options. By pushing our design to the limits of the design constraints, we were able to settle an optimal blade geometry for power output, defined by a unique chord and pitch distribution.

![Shaded rendering of earlier version]({{ "/assets/images/testing_flowchart.png" | relative_url }}){: .inline-image-r style="width: 400px"}

The blade was modeled in Autodesk Fusion 360 and 3D printed out of grey resin using the Cornell Rapid Prototyping Lab. Its performance was tested in a suction wind tunnel. The wind turbine setup included a rotation rate sensor and particle torque brake to allow for power calculation. Testing procedure can be seen right. The blade was subjected to multiple different wind environments, each with steady flow at a different velocity. We controlled voltage inputs of the torque brake to monitor how power output changed with rotation rate.

![Photo of old radio]({{ "/assets/images/power_curves.png" | relative_url }}){: .inline-image-l style="width: 600px; height: 300px;"}

The figure (left) shows a graph of each power curve obtained through our testing. We analyzed the maximum power output and corresponding rotation rate at each wind speed alongside a theoretical wind environment. Throughout this project, I was responsible for CAD modeling and analysis of testing results, and I contributed to the group tasks of making design decisions, developing a testing procedure, and presenting the project to our peers.


