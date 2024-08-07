---
title: "Enhancing 3D reconstruction of textureless indoor scenes with IndoReal multi-view stereo (MVS)"
authors: 
- Tao Wang
- Vincent J.L. Gan

date: "2024-07-02T00:00:00Z"
doi: "https://doi.org/10.1016/j.autcon.2024.105600"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-7T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["journal"]

# Publication name and optional abbreviated publication name.
publication: "Automation in Construction"
publication_short: "AiC"

abstract: "3D reconstruction plays a pivotal role in capturing the built environment’s object shapes and appearances for diverse smart applications, such as indoor navigation and geometric digital twinning. Despite its significance, traditional Multi-View Stereo (MVS) techniques are ineffective in indoor environments, characterised by textureless walls, illumination variation, and other nuanced phenomena. Moreover, current learning-based MVS pipelines are often developed without considering indoor attributes and rely on costly ground truth data for performance optimisation. This paper presents the “IndoReal-MVS” dataset, a rich indoor-centric compilation reflecting real-world phenomena through advanced computer graphics. It also introduces unsupervised “IndoorMatchNet”, synergising Feature Pyramid Network (FPN) and Pyramid Flowformer (PFF) for encoding complex indoor geometries. The pipeline proposes Multi-Scale Feature loss, Superpixel-based Normal Consistency and Depth Smoothness losses, designed for indoor geometric characteristics. Experiments showcase a 192% relative improvement over the baseline model at stringent error thresholds, advancing indoor 3D reconstruction tasks."

# Summary. An optional shortened abstract.
summary: "This paper introduces the IndoReal-MVS dataset and the unsupervised IndoorMatchNet pipeline, significantly improving indoor 3D reconstruction with a 192% performance increase over traditional Multi-View Stereo (MVS) techniques, which struggle with textureless environments and require costly ground truth data."

tags:
- 3D Reconstruction
- IndoReal-MVS
- IndoorMatchNet
- Multi-View Stereo

featured: true

links:
- name: Custom Link
  url: https://doi.org/10.1016/j.autcon.2024.105600
url_pdf: https://doi.org/10.1016/j.autcon.2024.105600
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Tao Wang'
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
