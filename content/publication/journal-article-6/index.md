---
title: "Soft Robot Proprioception Using Unified Soft Body Encoding and Recurrent Neural Network"
authors:
- Liangliang Wang
- James Lam
- Xiaojiao Chen
- Jing Li
- Runzhi Zhang
- admin
- Zheng Wang
#author_notes:
#- "Fisr contribution"
#- "Equal contribution"
date: "2023-08-09T00:00:00Z"
doi: "https://doi.org/10.1089/soro.2021.0056"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Soft Robotics*"
publication_short: "SORO"

abstract: Compared with rigid robots, soft robots are inherently compliant and have advantages in the tasks requiring flexibility and safety. But sensing the high dimensional body deformation of soft robots is a challenge. Encasing soft strain sensors into the internal body of soft robots is the most popular solution to address this challenge. But most of them usually suffer from problems like nonlinearity, hysteresis, and fabrication complexity. To endow the soft robots with body movement awareness, this work presents a bioinspired architecture by taking cues from human proprioception system. Differing from the popular usage of smart material-based sensors embedded in soft actuators, we created a synthetic analog to the human muscle system, using paralleled soft pneumatic chambers to serve as receptors for sensing body deformation. We proposed to build the system with redundant receptors and explored deep learning tools for generating the kinematic model. Based on the proposed methodology, we demonstrated the design of three degrees of freedom continuum joint and how its kinematic model was learned from the unified pressure information of the actuators and receptors. In addition, we investigated the response of the soft system to receptor failures and presented both hardware and software level solutions for achieving graceful degradation. This approach offers an alternative to enable soft robots with proprioception capability, which will be useful for closed-loop control and interaction with environment.

# Summary. An optional shortened abstract.
summary: Proprioception, Soft pneumatic chamber, Receptor, Pressure information, Kinematic model, Receptor failure.


tags:
- Proprioception
- Soft pneumatic chamber
- Receptor
- Pressure information
- Kinematic model
- Receptor failure
featured: true

links:
- name: SoRo
  url: https://www.liebertpub.com/doi/abs/10.1089/soro.2021.0056
url_pdf: "files/Proprioception_Using_Unified_RNN.pdf"
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
#url_slides: "files/ICRA2020Presentation.pdf"
url_source: ''
#url_video: "https://www.youtube.com/watch?v=jMRQAr8MuPI&t=1s"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '[Overview of the proprioception architecture for soft robots and its analogy to the human sense of proprioception](https://www.liebertpub.com/doi/abs/10.1089/soro.2021.0056)'
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
