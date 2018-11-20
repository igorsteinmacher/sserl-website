+++
title = "Causal Distance Metric Based Assistance for Debugging After Compiler Fuzzing"
date = 2018-11-20T16:31:49-07:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-11-28T14:00:00-07:00
time_end = 2018-11-28T15:00:00-07:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Josie Holmes and Alex Groce (Northern Arizona University)" ]

# Abstract and optional shortened version.
abstract = "Measuring the distance between two program executions is a fundamental problem in dynamic analysis of software and useful in many test generation and debugging algorithms. This paper proposes a metric for measuring distance between executions and specializes it to an important application: determining similarity of failing test cases for the purpose of automated fault identification and localization in debugging based on automatically generated compiler tests. The metric is based on a causal concept of distance where executions are similar to the degree that changes in the program itself introduced by mutation cause similar changes in the correctness of the executions. Specifically if two failing test cases (for the original compiler) become successful due to the same mutant they are more likely to be due to the same fault. We evaluate our metric using more than 50 faults and 2800 test cases for two widely-used real-world compilers and demonstrate improvements over state-of-the-art methods for fault identification and localization."

abstract_short = ""

# Name of event and optional event URL.
event = ""
event_url = ""

# Location of event.
location = "SICCS #224"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
