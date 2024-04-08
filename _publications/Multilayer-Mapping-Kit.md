---
title: "Multilayer Mapping Kit for Autonomous UAV Navigation"
collection: IEEE Access
permalink: /publication/Multilayer-Mapping-Kit
excerpt: ''
date: 27 January 2021 
venue: 'Volume: 9'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9336584'
citation: 'S. Chen, H. Chen, C. -W. Chang and C. -Y. Wen, "Multilayer Mapping Kit for Autonomous UAV Navigation," in IEEE Access, vol. 9, pp. 31493-31503, 2021, doi: 10.1109/ACCESS.2021.3055066.'
---

Mapping, as the back-end of perception and the front-end of path planning in the modern UAV navigation system, draws our interest. Considering the requirements of UAV navigation and the features of the current embedded computation platforms, we designed and implemented a novel multilayer mapping framework. In this framework, we divided the map into three layers: awareness, local, and global. The awareness map is constructed in cylindrical coordinate, enabling fast raycasting. The local map is a probability-based volumetric map. The global map adopts dynamic memory management, allocating memory for the active mapping area, and recycling the memory from the inactive mapping area. We implemented this mapping framework in three parallel threads: awareness thread, local-global thread, and visualization thread. Finally, we evaluated the mapping kit in both the simulation environment and the real-world scenario with the vision-based sensors. The framework supports different kinds of map outputs for the global or local path planners. The implementation is open-source for the research community.