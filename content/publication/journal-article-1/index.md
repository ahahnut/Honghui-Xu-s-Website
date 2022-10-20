---
title: "Privacy-Preserving Mechanisms for Multi-Label Image Recognition"
authors:
  - admin
  - Zhipeng Cai
  - Wei Li
# author_notes:
#   - "Equal contribution"
#   - "Equal contribution"
date: "2022-08-23"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-23"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transaction on Knowledge Discovery from Data 16(4)"
publication_short: "TKDD"

abstract: Multi-label image recognition has been an indispensable fundamental component for many real computer vision applications. However, a severe threat of privacy leakage in multi-label image recognition has been overlooked by existing studies. To fill this gap, two privacy-preserving models, Privacy-Preserving Multi-label Graph Convolutional Networks (P2-ML-GCN) and Robust P2-ML-GCN (RP2-ML-GCN), are developed in this article, where differential privacy mechanism is implemented on the model’s outputs so as to defend black-box attack and avoid large aggregated noise simultaneously. In particular, a regularization term is exploited in the loss function of RP2-ML-GCN to increase the model prediction accuracy and robustness. After that, a proper differential privacy mechanism is designed with the intention of decreasing the bias of loss function in P2-ML-GCN and increasing prediction accuracy. Besides, we analyze that a bounded global sensitivity can mitigate excessive noise’s side effect and obtain a performance improvement for multi-label image recognition in our models. Theoretical proof shows that our two models can guarantee differential privacy for model’s outputs, weights and input features while preserving model robustness. Finally, comprehensive experiments are conducted to validate the advantages of our proposed models, including the implementation of differential privacy on model’s outputs, the incorporation of regularization term into loss function, and the adoption of bounded global sensitivity for multi-label image recognition.

# Summary. An optional shortened abstract.
summary: Two privacy-preserving models, Privacy-Preserving Multi-label Graph Convolutional Networks (P2-ML-GCN) and Robust P2-ML-GCN (RP2-ML-GCN), are developed in this article, where differential privacy mechanism is implemented on the model’s outputs so as to defend black-box attack and avoid large aggregated noise simultaneously.

# tags:
#   - Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/abs/10.1145/3491231
url_code: "https://github.com/ahahnut/-R-P2-ML-GCN"
# url_dataset: ""
# url_poster: ""
# url_project: ""
# url_slides: ""
# url_source: ""
# url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# projects: []
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
