---
title: "Autonomous flight in unknown and dynamic environment"
collection: Ph.D. Thesis
permalink: /publication/Autonomous-flight-in-unknown-and-dynamic-environment
excerpt: ''
date: 2023 January
venue: 'Ph.D. Thesis'
paperurl: 'https://theses.lib.polyu.edu.hk/bitstream/200/12277/3/6724.pdf'
citation: 'Chen, Han. "Autonomous flight in unknown and dynamic environment." (2023).'
---

The development of aerial robots in recent years has involved Micro Aerial Vehicle (MAV) more and more in our daily life. MAVs, especially quadrotors, have been widely used in field applications, such as disaster response, field surveillance, and search-and-rescue. For accomplishing such missions in challenging environments which narrow free space, crowded obstacles, and intruding and moving objects, the capability of navigating with full autonomy without collision is the most crucial requirement. This thesis is arising from the real-world applications of MAVs, and we present novel methodologies, complete system designs, and progressive test results in simulation and field robots, with a focus on the adaptability to cheap and affordable hardware platforms. Also, a basic requirement is finishing all the autonomous navigation task with onboard resources only, no external guidance is required. We start by introducing a computing efficient motion planning algorithm which is more concise and outperform existing autonomous navigation system of UAVs in single-step calculation time. Later, based on the above research, we developed a path planner working on the map which is much larger than the camera FOV to guide the local motion planner and avoid potential detours, confronting a more complex and dense environment. To better avoid those continuously moving obstacles, after that we propose a velocity planning algorithm based on the relative velocities toward obstacles in the environment and implicitly include the future obstacle's position. A novel lightweight pointcloud-based obstacle tracking and velocity estimation algorithm is also designed to fulfill a complete system. At last, we improve the robustness of the dynamic object perception part by introducing the image-based object detector and tracker and active yaw control, enhance the flight smoothness and speed by the polynomial trajectory optimization approach, and upgrade flight safety by involving object state's uncertainty. Extensive experimental and contrasting results, and detailed system set-up are presented throughout the thesis. We conclude this thesis by introducing the motivation backside each chapter and summarizing the current limitation of the aerial autonomy development, and propose future potential research opportunities based on our research experience.