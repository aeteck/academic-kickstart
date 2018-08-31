+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "Magnetic Levitation"

# Project summary to display on homepage.
summary = "Magnetic levitation controls problem."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "maglev.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["control", "system-identification", "electronics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
![Maglev IRL](/img/maglev.png)
The magnetic levitation system was a project also completed for the controls engineering course at Berkeley (MEC134). The goal of this project was to implement a purely analog controller to levitate a metallic ball in a magnetic field.

This project emphasized system identification via a “gray-box” method of the system as opposed to “white-box” modeling. Thus, many data points were taken to create a mathematical model to be able to control with the right components. Through analysis, it was found that in order to control this system easily, the system first had to be linearized.

Different controller design techniques were implemented in this project such as: Use of the bode plot, root locus method, and implementing MATLAB tools to design a lead compensator.

To view the extensive documentation: {{% staticref "files/maglev.pdf" "newtab" %}}PDF [14.1MB]{{% /staticref %}}.

To see a demo of the ball levitating, see: {{< youtube 1TiKO9B2M_s>}}

*Learning outcomes include: System identification techniques, MATLAB reinforcement, electronics debugging, documentation.*
