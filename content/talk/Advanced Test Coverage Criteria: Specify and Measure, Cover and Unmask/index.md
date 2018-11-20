+++
title = "Advanced Test Coverage Criteria: Specify and Measure, Cover and Unmask"
date = 2018-11-20T16:34:37-07:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-09-28T10:30:00-07:00
time_end = 2018-09-28T11:30:00-07:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Nikolai Kosmatov (CEA List, France) " ]

# Abstract and optional shortened version.
abstract = "Automatic test data generation (ATG) is a major topic in software engineering. A large amount of research effort has been invested to automate white-box testing. While a wide range of different and sometimes heterogeneous code-coverage criteria have been proposed, testing techniques still lack a generic formalism to describe them all, and available test automation tools usually support only a small subset of them. This talk brings the audience to a journey into the world of white-box testing criteria and their automated support. We try to bridge the gap between the coverage criteria supported by state-of-the-art white-box ATG technologies, such as Dynamic Symbolic Execution, and advanced coverage criteria found in the literature. The talk is articulated around labels, a recent specification mechanism for test objectives, and their effective support in automated testing tools. Labels are generic enough to *specify* many common testing criteria, and amenable to efficient automation making it possible to *cover* the corresponding test objectives and to *measure* the coverage level of a given test suite. We propose several optimization techniques resulting in an effective support for labels in ATG tools. We also show how a combination of static analysis techniques can be efficiently applied to detect — *unmask* — infeasible test objectives that are responsible for waste of test generation effort and imprecise coverage measurement. We demonstrate the LTest toolset for test automation with efficient support of labels. Finally, we present a recent extension of labels, called HTOL (Hyperlabel Test Objectives Language), capable to encode even most advanced test coverage criteria (such as variants of MCDC, dataflow criteria, non-interference properties, etc.), including hyperproperties. This talk is based on a series of recent research and tool implementation efforts [ICST 2014, TAP 2014, ICST 2015, ICST 2017t, ICST 2017r, ICSE 2018]. It is a joint work with S.Bardin, M.Delahaye, M.Marcozzi, M.Papadakis, V.Prevosto et al."

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
