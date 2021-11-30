---
title: "CrystalBall: Statically Analyzing Runtime Behavior via Deep Sequence Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- "Stephen A. Zekany"
- "Daniel Rings"
- "Nathan Harada"
- "Michael A. Laurenzano"
- "Lingjia Tang"
- "Jason Mars"


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# -
# -

date: "2016-10-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2016-10-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Symposium on Microarchitecture (MICRO '16)*
publication_short: In *Symposium on Microarchitecture (MICRO '16)*

abstract: Understanding dynamic program behavior is critical in many stages of the software development lifecycle, for purposes as diverse as optimization, debugging, testing, and security. This paper focuses on the problem of predicting dynamic program behavior statically. We introduce a novel technique to statically identify hot paths that leverages emerging deep learning techniques to take advantage of their ability to learn subtle, complex relationships between sequences of inputs. This approach maps well to the problem of identifying the behavior of sequences of basic blocks in program execution. Our technique is also designed to operate on the compiler’s intermediate representation (IR), as opposed to the approaches taken by prior techniques that have focused primarily on source code, giving our approach language independence. We describe the pitfalls of conventional metrics used for hot path prediction such as accuracy, and motivate the use of Area Under the Receiver Operating Characteristic curve (AUROC). Through a thorough evaluation of our technique on complex applications that include the SPEC CPU2006 benchmarks, we show that our approach achieves an AUROC of 0.85.

# Summary. An optional shortened abstract.
summary: Understanding dynamic program behavior is critical in many stages of the software development lifecycle, for purposes as diverse as optimization, debugging, testing, and security. This paper focuses on the problem of predicting dynamic program behavior statically. We introduce a novel technique to statically identify hot paths that leverages emerging deep learning techniques to take advantage of their ability to learn subtle, complex relationships between sequences of inputs. 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
# - name: "Course Repository"
#   url: https://github.com/jieltan/OpenCompArchCourse

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'CrystalBall_Slides.key'
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
