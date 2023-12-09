---
title: "Model order reduction of time-domain vibro-acoustic finite element simulations with non-locally reacting absorbers"
authors:
- admin
- Sjoerd vna Ophem
- Wim Desmet
- Elke Deckers
author_notes:
- ""
- ""
date: "2015-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Computer Methods in Applied Mechanics and Engineering"
publication_short: "CMAME"

abstract: "Time-domain vibro-acoustic finite element simulation gained considerable interest in recent years because of the rise of some applications such as auralization and virtual sensing. Efficiency and stability are of great importance for this topic. The number of elements needed per wavelength to reach acceptable accuracy often results in a large model size, which requires lots of computational resources and cannot run efficiently. Model order reduction can significantly alleviate this problem by reducing the size of these models, while maintaining the high-fidelity property. However, many model order reduction techniques fail to preserve the stability for non-locally reacting absorbers, which are often accounted for by using the Helmholtz equation with frequency-dependent density and bulk modulus, known as the equivalent fluid method. When discretized into a finite element model, frequency-dependent mass and stiffness matrices are introduced, which hinder the preservation of stability in the context of model order reduction. This paper presents a method that enables the creation of a stable reduced order model of a vibro-acoustic system with non-locally absorbers. This method reforms the Helmholtz equation and considers it as the interconnection of several passive systems. Stacking the states of these subsystems gives the final descriptor representation of the non-locally reacting absorbers. Furthermore, a possible second-order representation of the descriptor model is chosen such that it satisfies the stability-preserving condition under model order reduction. The resulting second-order model is coupled with a vibro-acoustic system in a velocity potential-displacement formulation, leading to a second-order model satisfying the aforementioned stability-preserving condition. The proposed method is successfully verified by several numerical simulations."

# Summary. An optional shortened abstract.
summary: "vibro-acoustics; finite element method; non-locally reacting absorbers; model order reduction; time domain"

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

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
slides: example
---
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
