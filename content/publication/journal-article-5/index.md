---
title: "Kinematic Analysis of Soft Continuum Manipulators Based on Sparse Workspace Mapping"
authors:
- Jing Li
- Xiaojiao Chen
- admin
- Wenping Wang
- James Lam
- Zheng Wang
#author_notes:
#- "Fisr contribution"
#- "Equal contribution"
date: "2022-02-24T00:00:00Z"
doi: "10.1109/LRA.2022.3154007"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of IEEE Robotics and Automation Letters*"
publication_short: "RAL"

abstract: Soft robots, with advantages of high adaptability to the environment, relatively easy and simple fabrication process as well as promising performances, have been thoroughly investigated and widely applied lately, the superiority of which has been proved in areas such as medicine, industry, daily life service and so on. However, it is still challenging to realize stable, efficient, and accurate control of soft robots due to their high compliance and hyper-redundancy. One of the main causes is the difficulty in building an accurate model for analyzing the relation between control input and output (force and/or deformation). In this letter, we proposed an intuitive approach for solving inverse kinematics of soft manipulators, where the relation between actuation pressures and end-effector motions was established by analyzing the sampled workspace from a real platform. A quantitative measurement between control accuracy and computational efficiency was performed and applied in achieving a reasonable balance in between. Based on the proposed approach, real-time motion tracking of a self-developed soft manipulator was implemented on Raspberry Pi taking less than 10 ms and the tracking error was 3.35% of the full workspace in average, comparable to the system capability. Our approach has validated the feasibility of fast searching in finding inverse kinematics solutions with satisfactory accuracy and simple implementation process and demonstrated its potential in working as the basis in advanced control.

# Summary. An optional shortened abstract.
summary: Modeling, Control, and Learning for Soft Robots.


tags:
- modeling
- soft manipulators
- sparse searching
- Inverse kinematics
featured: true

links:
- name: IEEE
  url: https://ieeexplore.ieee.org/document/9721061
url_pdf: "files/Sparse-Workspace-Mapping.pdf"
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
  caption: '[The proposed workplace sampling, gridding and searching approach to the soft manipulator.](https://ieeexplore.ieee.org/document/9721061/figures#figures)'
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
slides: ""
---
<!-- {{< figure src="featured.png" title="The file structure of workplace" numbered="true" >}} -->
<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}} -->

<!-- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
