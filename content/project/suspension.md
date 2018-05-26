+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "HPV Suspension"

# Project summary to display on homepage.
summary = "Compact and integrated suspension design on a recumbent tricycle."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "susp.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["machine-design", "manufacturing", "CAD"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
![Suspension assembly](/img/susp_irl.jpeg)

This project was completed with the UC Berkeley Human Powered Vehicle Team’s suspension sub-team for the 2017 vehicle, BLT – the second tricycle iteration of the team. We were tasked with designing and manufacturing a suspension system of our choice, with consideration of track width, weight, stability, and traction in mind. The initial decision was whether to improve on the previous vehicle’s system, a classical double wishbone system, or design a completely different one.

As such, we decided it was better to implement a new design, due to the double wishbone system’s bulkiness and unnecessary features for a tricycle. The final design was heavily influenced by ICE Tricycle’s front suspension system. Our design consisted of a four bar mechanism, where the upper link connected to the frame by way of a steerer tube, and the lower link connected to the front wheel by a spindle. Two H-links connect the upper and lower links together to move the lower link in a prescribed path. In addition, a Fox Float DPS shock was incorporated and is mounted between the upper and lower links to allow 1.25 inches of travel. This designed proved to be advantageous due to the fact that it is extremely compact and all suspension movement and dynamics are planar with the steering knuckle (i.e. there are no moving parts outside of the steering knuckle plane). One disadvantage from this design, however, was the fact that the system did not allow camber angle change under compression. As such, a high caster angle of 12º was chosen to compensate, as the camber angle will increase when the wheels are turned.

![Side view](/img/hpv_side.jpg) ![Top view](/img/hpv_top.jpg)

This design was finalized with the help of some Finite Element Analysis simulations performed in SolidWorks. Although I was not the one who performed the actual simulations, I aided in creating the load models associated with the simulations. In particular, we were interested in three different loading cases: lateral loads under cornering, braking forces under deceleration, and reaction forces when impacting a speed bump (as the competition incorporates a speed bump during the race). The results from the FEA simulations helped us refine the parts until a desired factor of safety was achieved.

{{< figure src="/img/susp_corner.png" title="Example of stress FEA due to cornering." >}}

While the design phase occurred during the Fall semester, manufacturing was taken into consideration. As such, most parts were designed to be CNC machined, while the only parts designed to be hand-machined were the wheel spindles. However, as we designed for a press fit, the spindle had to be machined to be within a 0.0005” tolerance to be correctly fit with the lower link.

The suspension system proved itself to be a very useful advantage compared to other teams as our vehicle did not tip over during competition. It also allowed the vehicle to clear obstacles such as the speed bump and the rumble strip at much higher speeds than other vehicles, resulting in severely reduced lap times. To see the suspension system in action, see: {{< youtube SN3OsCNo_kY>}}

*Learning outcomes include: Team communication skills, design methods for manufacturing, vehicle (suspension) dynamics.*
