---
layout: project
type: project
image: images/worldmodel/thumb.jpg
title: Robotic World Model using a Graph Database Backend
permalink: projects/worldmodel
# All dates must be YYYY-MM-DD format!
date: 2017-10-01
labels:
  - Python
  - Application
  - Infrastructure
  - ROS
summary: Development of a scene-graph based robotic world model component used for storing and querying information about task-relevant objects in the robot's environment.
---

<img class="ui fluid bordered image" src="../images/worldmodel/world_neo4j.jpg">

### Highlights
- database backend based on Neo4J
- entity schema and object-graph mapping (OGM) from stored entities in the database to Python class instances
- pre-defined world model operations (e.g. add/remove objects, query relative transformation between arbitrary objects, load/dump graph from/to yaml files, ...)
- pre-defined utility queries (e.g. object triples with certain properties) along-side full flexibility of CYPHER (Neo4j's graph query language)
- interfaces to ROS

### Further Material
- [1] Lehner, Peter, Sebastian Brunner, Andreas Dömel, Heinrich Gmeiner, Sebastian Riedel, Bernhard Vodermayer, and Armin Wedler. <a href="https://ieeexplore.ieee.org/abstract/document/8396726/">"Mobile manipulation for planetary exploration."</a> In 2018 IEEE Aerospace Conference, pp. 1-11. IEEE, 2018.

<hr>
**Technology Stack:** Python, Neo4J, neomodel, ROS

**Work Affiliation:** German Aerospace Center (DLR), in collaboration with Andreas Dömel, Sebastian Brunner, Peter Lehner
