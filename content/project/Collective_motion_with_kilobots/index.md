---
title: Collective motion with kilobots
summary: Using kilobots to simulate collective behaviors of living microorganisms.
tags:
- Swarming
date: "2020-09-22T00:00:00Z"


reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?


external_link: ""

# Optional header image (relative to `static/media/` folder).

image:
  caption: Swarming
  focal_point: Smart

links:
- icon: bacteria
  icon_pack: fas
  name: Zhang's lab
  url: https://ins.sjtu.edu.cn/people/hpzhang/index_en.html
---
From bacterial colonies measured in micrometers to flocks of birds and fish schools measured in centimeters, nature is filled with examples of collective motion. In collective motion, vast numbers of simple and self-propelled individuals, after aggregating, show complex physical phenomena and capabilities. Biological organisms achieve robust high-level behaviours by combining and coordinating stochastic low-level components.
{{< figure src="Robot.png" title="Robot Designed" >}}
However, due to the limitations of physical structures and classic control algorithm, it is challenging to reproduce and control the collective motion in multi-robot system. In this paper, we study a simple yet robust collective motion called Flashing Ratchet. In our designed system, each robot does not possess individual identity or addressable position yet can move stochastically towards to the darker position.
{{< figure src="Robot_movement.png" title="Robot Movement" >}}
Though possessing strong stochasticity, we prove theoretically, numerically and experimentally that suitable time and space parameters provided, Flashing Ratchet can be used to control vast number of robots. After 5 on-offs, 75% of the robots can move directionally. This study indicates that stochastic systems may offer an alternative approach to design robot system with more complex behaviors and stronger robustness.
{{< figure src="Mechanism_ratchet.jpg" title="Flashing Ratchet Mechanism from  [Paper](https://royalsocietypublishing.org/doi/10.1098/rsos.171685#:~:text=The%20flashing%20Brownian%20ratchet%20is,discrete%20in%20time%20and%20space.)" >}}

