+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "PERCA"

# Project summary to display on homepage.
summary = "2-axis real-time reading and speaking device."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "perca.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["machine-design", "control", "manufacturing", "electronics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
![PERCA Render](/img/perca.png)

This project was completed in a group of five students for a Microprocessor-Based Mechanical Systems course (ME135). The overall objective of the course was to create a mechanical system that utilizes a microprocessor’s capability to run in real-time and multitask. To that end, our team decided to create a product capable of reading a piece of text out loud to the user.

The motivation of this project was to assist the visually impaired who cannot read documents. Originally, the team set out the create a small portable rover similar to ZutALabs’s Mini Robotic Printer. However, this proved to be quite cumbersome and expensive design-wise, as compacting the product didn’t necessarily help achieve the task of multitasking and operating in real-time. Thus, it was decided that it would be better to design the product in a simple 2-axis CNC-like manner to offer the same functionality but with less mechanical tolerance complexities.

PERCA was powered and operated by the National Instruments myRIO microcontroller running LabVIEW to control two stepper motors and communicate with a computer webcam. The myRIO code incorporated a state machine architecture in order to integrate all sub Virtual Instruments (VIs).

{{< figure src="/img/perca_vi.png" title="An example of a VI responsible for changing lines." >}}

When it came time to present the product, PERCA worked flawlessly and met its objective of being able to scan a page and read it out loud in real-time. To view a timelapse of PERCA in action, please see the following: {{< youtube HWrEg3_ONYw>}}

*Learning outcomes of this project include: Machine design, learning another programming language (LabVIEW), team communication, microcontroller basics.*
