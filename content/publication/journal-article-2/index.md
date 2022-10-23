---
title: "Audio-Visual Autoencoding for Privacy-Preserving Video Streaming"
authors:
  - admin
  - Zhipeng Cai
  - Daniel Takabi
  - Wei Li
# author_notes:
#   - "Equal contribution"
#   - "Equal contribution"
date: "2021-06-07"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-24"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Internet of Things Journal 9(3)"
publication_short: "IoTJ (Impact Factor: 9.936)"

abstract: The demand of sharing video streaming extremely increases due to the proliferation of Internet of Things (IoT) devices in recent years, and the explosive development of artificial intelligent (AI) detection techniques has made visual privacy protection more urgent and difficult than ever before. Although a number of approaches have been proposed, their essential drawbacks limit the effect of visual privacy protection in real applications. In this article, we propose a cycle vector-quantized variational autoencoder (cycle-VQ-VAE) framework to encode and decode the video with its extracted audio, which takes the advantage of multiple heterogeneous data sources in the video itself to protect individuals’ privacy. In our cycle-VQ-VAE framework, a fusion mechanism is designed to integrate the video and its extracted audio. Particularly, the extracted audio works as the random noise with a nonpatterned distribution, which outperforms the noise that follows a patterned distribution for hiding visual information in the video. Under this framework, we design two models, including the frame-to-frame (F2F) model and video-to-video (V2V) model, to obtain privacy-preserving video streaming. In F2F, the video is processed as a sequence of frames; while, in V2V, the relations between frames are utilized to deal with the video, greatly improving the performance of privacy pro- tection, video compression, and video reconstruction. Moreover, the video streaming is compressed in our encoding process, which can resist side-channel inference attack during video transmission and reduce video transmission time. Through the real-data exper- iments, we validate the superiority of our models (F2F and V2V) over the existing methods in visual privacy protection, visual quality preservation, and video transmission efficiency.

# Summary. An optional shortened abstract.
summary: We propose a cycle vector-quantized variational autoencoder (cycle-VQ-VAE) framework to encode and decode the video with its extracted audio, which takes the advantage of multiple heterogeneous data sources in the video itself to protect individuals’ privacy.

# tags:
#   - Source Themes
featured: True

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9453730
url_code: "https://github.com/ahahnut/cycle-VQ-VAE"
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
