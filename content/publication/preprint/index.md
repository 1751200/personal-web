---
title: "Image change detection with only a few samples"
authors:
- Ke Liu
- Zhaoyi Song
- Haoyue Bai

author_notes:
  - 'Equal Contribution'
  - 'Equal Contribution'

date: "2020-04-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:submit/5217595 [cs.AI]"
publication_short: "arXiv preprints"

abstract: This paper considers image change detection with only a small number of samples, which is a significant problem in terms of a few annotations available.
  A major impediment of image change detection task is the lack of large annotated datasets covering a wide variety of scenes.
  Change detection models trained on insufficient datasets have shown poor generalization capability.
  To address the poor generalization issue, we propose using simple image processing methods for generating synthetic but informative datasets, and design an early fusion network based on object detection which could outperform the siamese neural network. Our key insight is
  that the synthetic data enables the trained model to have good generalization ability for various scenarios. We compare the model
  trained on the synthetic data with that on the real-world data captured
  from a challenging dataset, CDNet, using six different test sets. The results demonstrate that the synthetic
  data is informative enough to achieve higher generalization ability than the insufficient real-world data. Besides, the experiment shows that utilizing a few (often tens of) samples to fine-tune
  the model trained on the synthetic data will achieve excellent results.

# Summary. An optional shortened abstract.
summary: A power plant aimed to detect anomalies in surveillance footage. Given the scarcity of real-world data, realized a strategy to develop a synthetic dataset and train models to detect discrepancies in the footage.

tags: [Pattern Recognition, Digital Image Processing, Artificial Intelligence]
featured: false

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/submit/5217595/view
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Some examples of the image pairs and detection results.'
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
#   E.g. `slides: "iros23"` references `content/slides/iros23/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
