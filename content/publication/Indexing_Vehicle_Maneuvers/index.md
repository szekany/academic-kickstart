---
title: "Finding and Indexing Vehicle Maneuvers from Dashboard Camera Video"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- "Stephen A. Zekany"
- "Thomas F. Larsen"
- "Ronald G. Dreslinski"
- "Thomas F. Wenisch"

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In IEEE Transactions on Intelligent Transportation Systems
publication_short: In ITS-Transactions

abstract: A key challenge for self-driving vehicle researchers is to curate massive instrumented vehicle data sets. A common task in their development workflow is to extract video segments that meet particular criteria, such as a particular road scenario or vehicle maneuver. We present a novel approach for detecting vehicle maneuvers from monocular dash-cam video building upon a deep learning visual odometry model (DeepV2D) to estimate frame-accurate ego-vehicle movement. We classify move- ment sequences against reference maneuvers using dynamic time warping and simple heuristics. We describe, implement, and evaluate classifiers to recognize individual maneuvers. We show that using deep learning visual odometry to estimate location is superior to consumer-grade high-resolution GPS for this application. We describe and implement a greedy approach to classify maneuvers and evaluate our approach on common road maneuvers. We find an overall AUROC value of 0.91 for turns, 0.92 for lane changes, and 0.93 for deceleration.

# Summary. An optional shortened abstract.
summary: We describe, implement, and evaluate classifiers to recognize individual vehicle maneuvers. We show that using deep learning visual odometry to estimate location is superior to consumer-grade high-resolution GPS. We describe and implement a greedy approach to classify maneuvers and evaluate our approach on common road maneuvers.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Slides (PPT)
#   url: https://docs.google.com/presentation/d/1LXJC9QWPG4b4gz-O9UTQtca3YiC0Ub9T/edit?usp=sharing&ouid=117370703190601304810&rtpof=true&sd=true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
