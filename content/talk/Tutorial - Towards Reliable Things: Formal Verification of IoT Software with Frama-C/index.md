+++
title = "Tutorial   Towards Reliable Things: Formal Verification of IoT Software With Frama C"
date = 2018-11-20T16:44:27-07:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-10-12T08:45:00-07:00
time_end = 2018-10-12T11:15:00-07:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Allan Blanchard (Inria Lille Nord Europe, France)",
	    "Frédéric Loulergue (Northern Arizona University, SICCS)" ]

# Abstract and optional shortened version.
abstract = "Among distributed systems, connected devices and services, also referred to as the Internet of Things (IoT), have proliferated very quickly in the past years. There are now billions of interconnected devices, and this number is growing. It is anticipated that by 2021, about 46 billions of devices will be in use. Some of these devices are in service in safety and security critical domains, and even in domains that are not necessarily critical, privacy issues may arise with devices collecting and transmitting a lot of personal information. Formal methods have been used successfully for years in highly critical domains, now they can help to bring security into the IoT field. In practice it is common to rely on a combination of formal methods to achieve an appropriate degree of guarantee: static analyses to guarantee the absence of runtime errors, deductive verification of functional correctness, dynamic verification for parts that cannot be proved using deductive verification. This tutorial is focused on Frama-C, which is a source code analysis platform that aims at conducting verification of industrial-size programs written in ISO C99 source code. Frama-C fully supports the combination of formal methods approach, by providing to its users with a collection of plug-ins that perform static and dynamic analysis for safety and security critical software. Moreover collaborative verification across cooperating plugins is enabled by their integration on top of a shared kernel, and their compliance to a common specification language ACSL. Recently Frama-C has been applied to the verification of software in the context of the Internet of Things."
abstract_short = ""

# Name of event and optional event URL.
event = ""
event_url = ""

# Location of event.
location = "SICCS #223"

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
url_code = "https://www.dropbox.com/s/b6r25l5wz1rw0xm/Frama-C_Tutorial.ova?dl=0"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
