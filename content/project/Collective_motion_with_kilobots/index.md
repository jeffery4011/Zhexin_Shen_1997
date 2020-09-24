---
title: Collective_motion_with_kilobots
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
  caption: One version of our kilobots
  focal_point: Smart

links:
- icon: bacteria
  icon_pack: fas
  name: Zhang's lab
  url: https://ins.sjtu.edu.cn/people/hpzhang/index_en.html
---
We focus on simulating collective behaviors of living microorganisms with multiple simple robots. The present goal of this project is to reproduce the result of [Paper](https://arxiv.org/abs/1606.09559). 
{{< figure src="behaviors.jpg" title="Target Results" >}}
We set up a plat form for the experiments. The bottom of this plat form is a LCD TV where we can show images and videos through Matlab program to mimic different environments.
{{< figure src="Interior_environment.jpg">}}
All the platform is covered by black cloth to prevent the influence of noises of exterior illumination.
{{< figure src="Exterior_environment.jpg">}}
We designed robots with “phototaxis” that vibrate when detecting light underneath them.
{{< video src="motion.mp4" controls="yes" >}}>
Several versions of robots have been tested to ensure stable movements.
{{< figure src="version_kilobot.jpg">}}
{{< figure src="version_kilobot1.jpg">}}
So far, we have experimented collevtive movements in different environments such as light waves and spot light circumstances. In light waves environment, we changed the velocity and width of the waves and comes to a qualitative conclusion that when there are wide waves with low velocity, the kilobot will follow a wave. When there are shallow waves with high velocity, time is too limited for kilobot to respond or catch up with. It will follow the wave for a little time and stop until next wave reaches. In spot light environment, the kilobot moves toward the spot light area.
{{< figure src="Condition.jpg">}}
