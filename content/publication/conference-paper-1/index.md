---
title: "Sample-Efficient Learning of Soft Task Priorities Through Bayesian Optimization"
authors:
- admin
- Yuquan Wang
- Abderrahmane Kheddar

date: "2018-06-01T00:00:00Z"
doi: "10.1109/HUMANOIDS.2018.8624974"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2018 IEEE-RAS 18th International Conference on Humanoid Robots*
publication_short: In *Humanoids*

abstract: In recent optimization task-space controller, hierarchical task prioritization can be made strict or soft within a given level. Soft hierachization is made using task weighting. Yet the latter is not automated and weights are set ad-hoc. This empirical approach could be time-consuming and even leads to an infeasible result. During a specific episode in order to approximate the evolution of the weight of a task, we assign a Radial basis function network(RBFN) to each of the tasks. We use the Bayesian Optimization procedure to regulate the RBFNs corresponding to different tasks based on performances indexes that are extracted for a fixed episode. We benchmark the proposed solution with a dual-arm manipulation simulation where multiple potentially conflicting tasks are involved. First of all We can find that the proposed approach outperforms a hand-tuned controller in terms of tracking errors. In comparison with tuning the weights using another stochastic optimization technique, i.e. CMA-ES, we can find that the proposed approach requires much less samples to evaluate.
# Summary. An optional shortened abstract.
summary: Task analysis, Optimization,Bayes methods, Robots, Tuning, Linear programming.

tags:
- Bayesian optimization
- Gaussian process
featured: true

links:
- name: IEEE
  url: https://ieeexplore.ieee.org/document/8624974/keywords#keywords
url_pdf: files/sample-efficient.pdf
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
  caption: '[The proposed frame](https://ieeexplore.ieee.org/document/8624974/keywords#keywords)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
