---
title: "Video Active Perception: Efficient Inference-Time Long-Form Video Understanding with Vision-Language Models"
authors:
- Martin Q. Ma
- Willis Guo
- Aditya Agrawal
- Ankit Gupta
- Paul Pu Liang
- Russ Salakhutdinov
- Louis-Philippe Morency
date: "2025-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *The Thirteenth International Conference on Learning Representations*
publication_short: In *ICLR 2025*

abstract: Large vision-language models (VLMs) have advanced multimodal tasks such as video question answering (QA), yet they struggle with long-form videos due to the computational burden of processing excessive tokens. Inspired by active perception theory, which posits that models gain information by acquiring data that differ from their expectations, we introduce Video Active Perception (VAP), a training-free method to enhance long-form video QA using VLMs. Our approach treats key frame selection as data acquisition in active perception and leverages a lightweight text-conditioned video generation model to represent prior world knowledge. Empirically, VAP achieves state-of-the-art zero-shot results on long-form video QA datasets such as EgoSchema, NExT-QA, ActivityNet-QA and CLEVRER, achieving an increase of up to 5.6 X efficiency by frames per question over standard GPT-4o, Gemini 1.5 Pro, and LLaVA-OV. Moreover, VAP shows stronger reasoning abilities than previous methods and effectively selects key frames relevant to questions. These findings highlight the potential of leveraging active perception to improve efficiency and effectiveness of long-form video QA.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: Abstract
  url: ''
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
