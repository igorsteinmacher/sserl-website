+++
title = "Parallel Programming With the Orleans Skeleton Library"
date = 2019-02-05T15:16:56-07:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2019-01-29T14:00:00-07:00
time_end = 2019-01-29T15:00:00-07:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Frederic Loulergue (Northern Arizona University)" ]

# Abstract and optional shortened version.

abstract = "As parallel architectures are now the norm, it is necessary to consider programming languages and libraries that offer a trade-off between execution efficiency and programming productivity.  While languages and libraries for high performance computing, such as MPI, favor efficiency over productivity, of lot of application domains require that mainstream programmers develop parallel applications without a huge knowledge about parallel programming. An algorithmic skeleton is a pattern of a classical parallel algorithm, and most often, an algorithmic skeleton also corresponds to a sequential algorithm. For example the map algorithmic skeleton applies a function to all the elements of a distributed collection and is related to the application of a function to a sequential collection. For the programmer, a parallel application is then obtained as the combination of several algorithmic skeletons. Orléans Skeleton Library (OSL) is a library of parallel algorithmic skeletons, written in C++ on top of MPI, which uses meta-programming techniques for optimization. Research on high-level parallel programming approaches systematically evaluate the performance of applications written using these approaches and informally argue that high-level parallel programming languages or libraries increase the productivity of programmers. In this talk, I will present OSL and a first attempt to evaluate the trade-off between programming effort and performance of applications developed using different programming models including OSL."

abstract_short = ""

# Name of event and optional event URL.
event = ""
event_url = ""

# Location of event.
location = "SICCS #308"

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
