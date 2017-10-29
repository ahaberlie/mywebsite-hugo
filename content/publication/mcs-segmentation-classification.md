+++
title = "Identifying Mesoscale Convective Systems in Radar Mosaics. Part I: Segmentation and Classification"
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
abstract = "This research evaluates the ability of image processing and select machine learning algorithms to identify mesoscale convective systems (MCSs) in radar reflectivity images for the conterminous United States.  The process used in this study is comprised of two parts: segmentation and classification.  Segmentation is performed by identifying contiguous or semi-contiguous regions of deep, moist convection that are organized on a horizontal scale of at least 100 km.  The second part, classification, is performed by first compiling a database of thousands of precipitation clusters, and then subjectively assigning each sample one of the following labels: 1) midlatitude MCS; 2) unorganized convective cluster; 3) tropical system; 4) synoptic system; and 5) ground clutter and/or noise.  The attributes of each sample, along with their assigned label, are used to train three machine learning algorithms: Random Forest, Gradient Boosting, and XGBoost.  Results using a testing dataset suggest that the algorithms can distinguish between MCS and non-MCS samples with high specificity and sensitivity.  Further, the trained algorithm predictions are well-calibrated, allowing reliable probabilistic classification.  The utility of this two-step procedure is illustrated by generating spatial frequency maps of automatically identified precipitation clusters that are stratified using various reflectivity and probabilistic prediction thresholds.  These results suggest that machine learning can add value by limiting the amount of false-positive (non-MCS) samples that are not removed by segmentation alone."

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
image = "headers/mcs-segment.png"
caption = "Example of MCS segmentation."

+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
