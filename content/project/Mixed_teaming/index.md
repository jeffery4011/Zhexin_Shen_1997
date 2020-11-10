---
title: Proficiency Aware Multi-Agent Actor-Critic for Mixed Aerial and Ground Robot Teaming
summary: Using MADRL algorithm with proficiency awareness to exploit the potential of a mixed team
tags:
- Mixed Cooperation
date: "2020-09-22T00:00:00Z"


reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?


external_link: ""

# Optional header image (relative to `static/media/` folder).

image:
  caption: Mixed Cooperation
  focal_point: Smart

links:
- icon: rotot
  icon_pack: fas
  name: Cognitive Robotics and AI Lab(CRAI)
  url: https://ruiliurobotics.weebly.com/research.html
---
  Mixed aerial and ground robot teaming, which involves ground vehicles (UGV) and unmanned aerialvehicles (UAVs), is widely used for ground criminal chasing,precise agriculture, and natural disaster rescue. 
  However, robot proficiency is different from each other that ground and aerialrobots are different in motion speed, perceiving range, and reaching area, and even tolerance to environment conditions. With the heterogeneous capabilities of robots’, it brings challenges of controlling as well as maximally exploiting a group of different robots. 
  Therefore, to address this challenge for effective ground and aerial teaming, this paper developed a pro-ficiency aware multi-agent deep reinforcement learning  (mix-RL) method to guide mixed teaming by adapting to capability difference of robot and task requirements.
{{< figure src="Environment.jpg" title="Simulated Kent State University Student Center, University Library and Risman Plaza" >}}
We use Gazebo to simulate the environment of Kent State University Student Center, University Library and Risman Plaza which includes diffenet conditions such as forests, buildings and plaza.
{{< figure src="Different_robots.jpg" title="Heterogenous Robots" >}}
We use three different kinds of vehicles in our simulation and each of them has distinct capabilities. 
* Firefly has redundant 6-rotor propulsion system which is very robust and guarantees broad perception. 
* Iris is a quad-copter. It moves faster but has a relative small range of perception. 
* Husky is a UGV with slow velocity. 
{{< figure src="Team_Comparison.jpg" title="Robot Team" >}}
We use a target-pursuing scenario as the task of our mixed team. The robots are seperated into two teams. Police(Blue) includes three different types of robots and its goal is to capture Criminal(Red). The criminal can also learn from each episode, thus we train our model with an adversarial training method.
{{< figure src="Tasks.jpg" title="Different Tasks" >}}
After training, the mixed team has a substaintial improvement compared with MADRL(without proficiency awareness) providing theoretical support for real-world teaming of aerial and ground robot deployment.
{{< figure src="Compare.PNG" title="A  Comparison  between  multi-robot  cooperation  with  and  without  proficiency-awareness" >}}
