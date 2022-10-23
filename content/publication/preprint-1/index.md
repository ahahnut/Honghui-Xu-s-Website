---
title: "Privacy-Preserving Multimodal Sentiment Analysis"
authors:
  - admin
date: "2022-09-13"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-09-13"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "Processing"

abstract: Multimodal sentiment analysis has been an indispensable fundamental component for many real applications. However, a severe threat of privacy leakage in the multimodal sentiment analysis has been overlooked by previous works. To fill this gap, we propose a Differentially Private Correlated Representation Learning (DPCRL) model to achieve privacy-preserving multimodal sentiment analysis by combining a correlated representation learning scheme with a differential privacy protection scheme. Our correlated representation learning scheme aims to transform high-dimension data transformation to meet the requirements of privacy-preserving multimodal sentiment analysis by learning the correlated and uncorrelated representations, where especially, an pre-determined correlation factor is employed to flexibly adjust the expected correlation among the correlated representations. The differential privacy protection scheme is used to obtain the disturbed correlated and uncorrelated representations by adding Laplace noise to for ε-differential privacy. In particular, the correlation factor can help alleviate the side-effect of the added Laplace noise on the sentiment prediction performance. Finally, via conducting a series of real-data experiments, we validate that our proposed DPCRL model is superior to the state-of-the-arts for privacy-preserving multimodal sentiment analysis.

# Summary. An optional shortened abstract.
summary: We propose a Differentially Private Correlated Representation Learning (DPCRL) model to achieve privacy-preserving multimodal sentiment analysis by combining a correlated representation learning scheme with a differential privacy protection scheme.

# tags:
#   - Source Themes
featured: True
# links:
#   - name: Custom Link
#     url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: "https://github.com/wowchemy/wowchemy-hugo-themes"
# url_dataset: "#"
# url_poster: "#"
# url_project: ""
# url_slides: ""
# url_source: "#"
# url_video: "#"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)"
#   focal_point: ""
#   preview_only: false
# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
