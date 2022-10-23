---
title: "Efficient CityCam-to-Edge Cooperative Learning for Vehicle Counting in ITS"
authors:
  - admin
  - Zhipeng Cai
  - Ruinian Li
  - Wei Li
# author_notes:
#   - "Equal contribution"
#   - "Equal contribution"
date: "2022-01-26"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-14"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transaction on Intelligent Transportation Systems 23(9)"
publication_short: "TITS (Impact Factor: 2.534)"

abstract: Vehicle counting is a fundamental component in Intelligent Transportation System (ITS) for city traffic man- agement. Although a number of vehicle counting approaches have been proposed, their essential drawbacks limit the effi- cacy of vehicle counting in real applications. In this paper, we propose a CityCam-to-Edge cooperative learning framework by cooperating multiple city cameras with an edge server to count vehicles more efficiently. Our learning framework consists of a lightweight feature extraction scheme deployed on the city cameras and a vehicle counting model implemented on the edge server. We devise the lightweight feature extraction scheme by leveraging multiple convolutional layers with few kernels in the design of deep learning architecture to reduce the utilization of parameters for feature extraction, so that the city cameras’ memory consumption and the data transmission time can be greatly reduced. Moreover, we design two novel vehicle counting models, F2F-M and O2O-M, to improve the counting performance by exploiting the temporal correlation among videos captured from multiple city cameras in a frame-to-frame manner and a video-to-video manner, respectively. By combining the lightweight feature extraction scheme and the proposed vehicle counting models, we obtain two end-to-end vehicle counting models, Lite-F2F-M and Lite-O2O-M. Finally, via conducting extensive experiments, we demonstrate that Lite-F2F-M and Lite- O2O-M models outperform the state-of-the-art in terms of vehicle counting accuracy and time efficiency.

# Summary. An optional shortened abstract.
summary: We propose a CityCam-to-Edge cooperative learning framework by cooperating multiple city cameras with an edge server to count vehicles more efficiently.

# tags:
#   - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9713742
url_code: "https://github.com/ahahnut/Lite-F2F-V2V-M"
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
