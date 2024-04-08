---
title: "A fast planning approach for 3D short trajectory with a parallel framework"
collection: Mechatronics
permalink: /publication/A-fast-planning-approach
excerpt: ''
date: 18 November 2023
venue: '5693-5699'
paperurl: 'https://linkinghub.elsevier.com/retrieve/pii/S0957415823001502'
citation: 'Chen, Han, et al. "A fast planning approach for 3D short trajectory with a parallel framework." Mechatronics 97 (2024): 103094.'
---

For real applications of unmanned aerial vehicles, the capability of navigating with full autonomy in unknown environments is a crucial requirement. However, planning a shorter path with less computing time is contradictory. To address this problem, we present a framework with the map planner and point cloud planner running in parallel in this paper. The map planner determines the initial path using the improved jump point search method on the 2D map, and then it tries to optimize the path by considering a possible shorter 3D path. The point cloud planner is executed at a high frequency to generate the motion primitives. It makes the drone follow the solved path and avoid the suddenly appearing obstacles nearby. Thus, vehicles can achieve a short trajectory while reacting quickly to the intruding obstacles.

We demonstrate fully autonomous quadrotor flight tests in unknown and complex environments with static and dynamic obstacles to validate the proposed method. In simulation and hardware experiments, the proposed framework shows satisfactorily comprehensive performance.