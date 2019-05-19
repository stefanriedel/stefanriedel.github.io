---
layout: project
type: project
image: images/robocup/thumb.jpg
title: RoboCup Logistics League - Autonomous Robotic Warehouse Logistics
permalink: projects/robocup
# All dates must be YYYY-MM-DD format!
date: 2014-07-01
labels:
  - C++
  - System Architecture
  - Trajectory Control
  - Infrastructure
summary: Participation (two-time winner, one 2nd place) at RoboCup Logistics League in 2011-2014, for which we developed a system of three collaborating robots solving material logistics in a warehouse scenario.
---

<div class="ui embed" data-source="youtube" data-id="_iesqH6bNsY" ></div>

### Overview

The RoboCup Logistics League offers a competition within a simulated industrial environment. In order to solve the logistical tasks, all three robots not only have to operate autonomously in a flexible, effective and robust way on their own, they should also collaborate efficiently in order to maximize the overall outcome. To this end, we implemented a custom-made solution (no ROS) based on the Festo Robotino platform involving robot hardware modifications and a holistic software system architecture solving task planning and execution, multi-robot collaboration, visual perception, motion planning and execution, and visualization/monitoring tools for game and robot states.

More details can be found in the publication linked below.

<div class="ui small rounded images">
  <img class="ui image" src="../images/robocup/robot.jpg">
  <img class="ui image" src="../images/robocup/gui.jpg">
  <img class="ui image" src="../images/robocup/detection.jpg">
  <img class="ui image" src="../images/robocup/traj.jpg">
</div>

### Responsibilities
- overall system and control architecture (with core team members)
- Linear-Segments-Parabolic-Blends (LSPB) trajectory generation
- PD trajectory control and shared-memory communication to actuator control deamon
- context-dependend camera configuration over Video4Linux-interface

### Further Material
- [1] Homepage: <a href="https://www.bbunits.de/">Bavarian Bending Units</a>
- [2] Jentzsch, Sören, Sebastian Riedel, Sebastian Denz, and Sebastian Brunner. <a href="https://link.springer.com/chapter/10.1007/978-3-642-39250-4_5">"TUMsBendingUnits from TU Munich: RoboCup 2012 logistics league champion."</a> In Robot Soccer World Cup, pp. 48-58. Springer, Berlin, Heidelberg, 2012.

<hr>
**Technology Stack:** C++, Boost, Eigen, Video4Linux

**Work Affiliation:** Technical University Munich (TUM), in collaboration with Sören Jentzsch, Peter Gschirr, Sebastian Brunner, Stefan Profanter, Sebastian Denz, Christian Ihrke, Sebastian Fischer and Ingmar Kessler
