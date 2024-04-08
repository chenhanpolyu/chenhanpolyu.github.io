---
title: "Computationally efficient obstacle avoidance trajectory planner for uavs based on heuristic angular search method"
collection: 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)
permalink: /publication/Computationally-efficient-obstacle
excerpt: ''
date: 2020/10/24
venue: '5693-5699'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9340778/'
citation: 'H. Chen and P. Lu, "Computationally Efficient Obstacle Avoidance Trajectory Planner for UAVs Based on Heuristic Angular Search Method," 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Las Vegas, NV, USA, 2020, pp. 5693-5699, doi: 10.1109/IROS45743.2020.9340778.'
---

For accomplishing a variety of missions in challenging environments, the capability of navigating with full autonomy while avoiding unexpected obstacles is the most crucial requirement for UAVs in real applications. In this paper, we proposed such a computationally efficient obstacle avoidance trajectory planner that can be used in unknown cluttered environments. Because of the narrow view field of single depth camera on a UAV, the information of obstacles around is quite limited thus the shortest entire path is difficult to achieve. Therefore we focus on the time cost of the trajectory planner and safety rather than other factors. This planner is mainly composed of a point cloud processor, a waypoint publisher with Heuristic Angular Search(HAS) method and a motion planner with minimum acceleration optimization. Furthermore, we propose several techniques to enhance safety by making the possibility of finding a feasible trajectory as large as possible. The proposed approach is implemented to run onboard in real-time and is tested extensively in simulation and the average control output calculating time of iteration steps is less than 18 ms.