---
title: "Neural Feature-Adaptation for Symbolic Predictions Using Pre-Training and Semantic Loss"
authors:
- Vedant Shah
- Aditya Agrawal
- Lovekesh Vig
- Ashwin Srinivasan
- Gautam Shroff
- Tanmay Verlekar
date: "2022-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: On *ArXiv (preprint)*
publication_short: On *ArXiv (preprint)*

abstract: We are interested in neurosymbolic systems consisting of a high-level symbolic layer for explainable prediction in terms of human-intelligible concepts; and a low-level neural layer for extracting symbols required to generate the symbolic explanation. Real data is often imperfect meaning that even if the symbolic theory remains unchanged, we may still need to address the problem of mapping raw data to high-level symbols, each time there is a change in the data acquisition environment or equipment. Manual (re-)annotation of the raw data each time this happens is laborious and expensive; and automated labelling methods are often imperfect, especially for complex problems. NEUROLOG proposed the use of a semantic loss function that allows an existing feature-based symbolic model to guide the extraction of feature-values from raw data, using `abduction'. However, the experiments demonstrating the use of semantic loss through abduction appear to rely heavily on a domain-specific pre-processing step that enables a prior delineation of feature locations in the raw data. We examine the use of semantic loss in domains where such pre-processing is not possible, or is not obvious. We show that without any prior information about the features, the NEUROLOG approach can continue to predict accurately even with substantially incorrect feature predictions. We show also that prior information about the features in the form of even imperfect pre-training can help correct this situation. These findings are replicated on the original problem considered by NEUROLOG, without the use of feature-delineation. This suggests that symbolic explanations constructed for data in a domain could be re-used in a related domain, by `feature-adaptation' of pre-trained neural extractors using the semantic loss function constrained by abductive feedback.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: Abstract
  url: 'https://arxiv.org/abs/2211.16047'
url_pdf: 'https://arxiv.org/pdf/2211.16047'
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
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
