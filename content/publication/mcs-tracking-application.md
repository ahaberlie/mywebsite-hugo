+++
title = "Identifying Mesoscale Convective Systems in Radar Mosaics. Part 2: Tracking and Application"
date = "2017-10-15"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["A. M. Haberlie", "W. S. Ashley"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "Journal of Applied Meteorology and Climatology (In Review)"
publication_short = "J. Appl. Climatol. Meteor. (In Review)"

# Abstract and optional shortened version.
abstract = "This research is Part 2 of a two-part study that evaluates the ability of image processing and select machine learning algorithms to detect, classify, and track mesoscale convective systems (MCSs) in radar reflectivity images for the conterminous United States. This paper focuses on the tracking portion of this framework. Tracking is completed through a two-step process using slice (snapshots of instantaneous MCS intensity) data generated in Part 1.  The first step is to perform spatiotemporal matching, which associates slices through temporally adjacent radar reflectivity images to generate swaths, or storm tracks.  When multiple slices are found to be matches, a difference-minimization procedure is used to associate the most similar slice with the existing swath.  Once this step is completed, a second step combines swaths that are spatiotemporally nearby.  Tracking performance is assessed by calculating select metrics for all available swath-building perturbations to determine the most optimal approach in tracking.  Frequency maps and time series generated from the swaths suggest that the spatiotemporal occurrence of these swaths is reasonable based on previous work.  Further, these events exhibit a diurnal cycle that is distinct from that of overall conterminous United States convection.  Finally, machine learning predictions are found to limit areas of high MCS frequency to the central and eastern Great Plains."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
#url_pdf = "http://onlinelibrary.wiley.com/doi/10.1002/joc.4461/full"
#url_preprint = 
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

#[[url_custom]]
#name = "Custom Link"
#url = "http://onlinelibrary.wiley.com/doi/10.1002/joc.4461/full"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
image = "headers/mcs-track.png"
caption = "29 June 2012 Derecho Track"

+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
