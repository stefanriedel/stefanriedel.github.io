---
layout: project
type: project
image: images/logview/logview_thumb.jpg
title: LogView - Interactive Visualization of Robotic Log Data 
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2018-06-18
labels:
  - done@DLR
  - Robotics
  - Data Visualization
summary: A viewer application I developed for integrated analysis of logged task-execution data with logged sensor data for our mobile manipulation platform.
---

<a href="https://raw.githubusercontent.com/SebastianRiedel/sebastianriedel.github.io/master/images/logview/logview.png" class="ui large right floated rounded image">
  <img src="../images/logview/logview_small.jpg">
</a>

The goal if this project was to bring together log data of our high-level task-/state-machine with the continuosly logged data of the sensors of our mobile manipulation robot [AIMM](https://www.dlr.de/rm/en/desktopdefault.aspx/tabid-11409/#gallery/29194). The results were presented at the Automatica Fair 2018.

### Responsibilities
- setting up and automating the continuous logging of all involved data streams on the robotic platform
- data pre-processing pipeline into suitable formats for querying/analysis
- interactive web viewer for displaying data streams for selected actions

<hr>
**Technology Stack:** Python, Pandas/Dask, HDF5, Bokeh, Datashader, ROS

**Work Affiliation:** German Aerospace Center (DLR)
