+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "Inverted Pendulum"

# Project summary to display on homepage.
summary = "Classic inverted pendulum on cart controls problem."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "ip.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["control", "simulation", "electronics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
![Inverted pendulum schematic](/img/ip.jpg)

The classic “inverted pendulum on a cart” control problem was done throughout the course of the semester with one other person for the second course in control systems at Berkeley (MEC134). As this project was completed throughout the course of the semester, many different aspects of control systems were explored as different modules including: Modeling, Simulation, Observer methods, LQR control, and Nonlinear control, to name a few.

The overall goal of this project was to implement a robust controller to successfully self-erect an inverted pendulum mounted on a cart capable of disturbance rejection. To accomplish this goal, many steps were taken. A model of the system first had to be generated to understand the dynamics occurring. Thus, the system identification aspect was implemented via the “white box” method, where each component of the system was modeled, including the electronics, to create differential equations to control the system. As this was a Single Input Multi Output (SIMO) system – namely, the input voltage controlled the cart position and the pendulum angular position, a state space representation was necessary to exploit the “pole placement” technique.

This project was completed using MATLAB and Simulink while the physical hardware was composed of Quanser’s QuaRC software and their Q4 DAQ. I was in charge of most components of the project including: Software simulation, laboratory testing, and experimental write-up. Ultimately, this project was successful and extremely valuable for controls knowledge.

To view the extensive documentation: {{% staticref "files/ip_compiled.pdf" "newtab" %}}(PDF){{% /staticref %}}.

To see a demo of the project in action: {{< youtube 6crAh9LXtlg >}}

*Learning outcomes include: Control systems fundamentals, modeling, simulation, expertise in MATLAB and Simulink, technical document preparation.*
