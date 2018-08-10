+++
title = "Ball Control using IR Proximity Sensor"
date = 2017-04-12T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["K. Hom", "C. Nakamura", "A. Tec"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["4"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract and optional shortened version.
abstract = "This lab explores a system using an infrared (IR) sensor and fan to control the position of a ping pong ball. The output voltage of the IR sensor and ball position were characterized by measuring the voltage using a custom LabVIEW VI and half-inch marks on the sides of the tube. These values were fit to a 3rd order polynomial using MATLAB. LabVIEW’s built in ProportionalIntegral Derivative (PID) control block was used to implement feedback control, with gains determined by trial and error. Noise, lack of significant figures, and faulty equipment initially led to high degrees of error in our system. After resolving theseissues, the feedback control implemented in our VI worked very well, with accurate steady state responses. The average height at steady state was within a half-inch of the desired height, with less than a half-inch standard deviation. Thus, PID control with an IR sensor to measure the displacement of the ball was sufficient to control the system relatively accurately."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["documentation", "measurement"]

# Links (optional).
url_pdf = "https://adolfotec.netlify.com/files/ball_ir.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

Written for a course in instrumentation and measurements, this is mainly here for my own sake.
