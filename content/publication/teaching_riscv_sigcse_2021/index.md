---
title: "RISC-V Reward: Building Out-of-Order Processors in a Computer Architecture Design Course with an Open-Source ISA"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- "Stephen A. Zekany"
- "Jielun Tan"
- "James A. Connolly"
- "Ronald G. Dreslinski"

# Author notes (optional)
author_notes:
 - "Equal contribution"
 - "Equal contribution"
 -
 -

date: "2021-03-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Symposium on Computer Science Education (SIGCSE '21)*
publication_short: In *Symposium on Computer Science Education (SIGCSE '21)*

abstract: We describe our experience teaching an undergraduate capstone (and elective graduate course) in computer architecture with a semester-long project in which teams of five students design and implement an out-of-order (OoO) pipelined processor core using the open-source RISC-V instruction set. The course content includes OoO scheduling algorithms for instructions to exploit instruction- level parallelism (ILP), example microarchitectures, caching, prefetching, and virtual memory. The labs and projects help students gain proficiency with the SystemVerilog language. Students use the concepts learned in class to design processors with the goals of achieving correctness and high performance for a suite of test programs representative of different data structures and algorithms. Using RISC-V enables students to validate and benchmark their designs by compiling test programs using GCC with a custom linker. By collaborating as a team, students learn how to write and debug a large code base over the two-month project. We explain the project content and process in detail, identify the challenges involved for students and the necessary instructor support, and share statistics and student feedback about the project. We have open-sourced our lab and project materials to enable others to teach similar courses.

# Summary. An optional shortened abstract.
summary: We describe our experience teaching an undergraduate capstone (and elective graduate course) in computer architecture with a semester-long project in which teams of five students design and implement an out-of-order (OoO) pipelined processor core using the open-source RISC-V instruction set.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: "Course Repository"
   url: https://github.com/jieltan/OpenCompArchCourse

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'SIGCSE_Slides.pptx'
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
