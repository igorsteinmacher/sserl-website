+++
title = "DeepState: Symbolic Unit Testing for C and C++"
date = 2018-11-20T16:37:10-07:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-09-28T11:30:00-07:00
time_end = 2018-09-28T12:30:00-07:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Alex Groce (Northern Arizona University)"]

# Abstract and optional shortened version.
abstract = "Unit testing is a popular software development methodology that can help developers detect functional regressions, explore boundary conditions, and document expected behavior. However, writing comprehensive unit tests is challenging and time-consuming, and developers seldom explore the obscure (and bug-hiding) corners of software behavior without assistance. DeepState is a tool that provides a Google Test-like API to give C and C++ developers push-button access to symbolic execution engines, such as Manticore and angr, and fuzzers, such as Dr. Fuzz. Rather than learning multiple complex tools, users learn one interface for defining a test harness, and can use various methods to automatically generate tests for software. In addition to providing a familiar interface to binary analysis and fuzzing for parameterized unit testing, DeepState also provides constructs that aid in the construction of API-sequence tests, where the tool chooses the functions or methods to call, allowing for even more diverse and powerful tests. By serving as a front-end to multiple tools, DeepState additionally provides a way to apply (novel) high-level strategies to test generation, and to compare effectiveness and efficiency of testing back-ends, including binary analysis tools."
abstract_short = ""

# Name of event and optional event URL.
event = ""
event_url = ""

# Location of event.
location = ""

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
