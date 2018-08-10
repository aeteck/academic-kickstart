+++
title = "Ball Control Using a Camera"
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
abstract = "This lab utilizes the same ping pong ball tower used in the previous lab, but with vision acquisition from a PlayStation Eye camera used to measure and control the position of the centroid of the ball. LabVIEW’s Vision Assistant block and several vision filters were used to accurately find the ball’s centroid. The ping pong ball’s position and the fan voltage were correlated using a linear equation to implement position control of the ball. This controller yielded results less accurate than our previous PID control for the IR sensor, but was still accurate enough to control the ping pong with a fairly close level of accuracy."
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
url_pdf = "https://adolfotec.netlify.com/files/ball_camera.pdf"
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
