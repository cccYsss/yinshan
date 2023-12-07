---
title: "Model order reduction of time-domain vibro-acoustic finite element simulations with admittance boundary conditions for virtual sensing applications"
authors:
- admin
- Sjoerd van Ophem
- Wim Desmet
- Elke deckers
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
publication: "Mechanical Systems and Signal Processing"
publication_short: "MSSP"

abstract: "Virtual sensing employs an estimator that combines a numerical model and a limited set of measurements to estimate the full field pressure of a vibro-acoustic system in the time domain. A key aspect of virtual sensing is to create a reduced-order model of the vibro-acoustic system, such that the numerical model can be effectively employed in the virtual sensing scheme. This paper aims to create a reduced-order vibro-acoustic finite element model with frequency-dependent admittance boundary conditions for virtual sensing applications using a Kalman filter. The frequency-dependent components in admittance boundary conditions always result in a frequency-dependent damping matrix which hinders the modeling in the time domain. This paper first treats the vibro-acoustic system as a negative feedback interconnection of two subsystems: a state-space model of admittance transfer functions and a vibro-acoustic system with rigid boundary conditions. Stacking the states of these two subsystems gives the final descriptor system. Then, due to the passivity of the admittance transfer function and the definiteness of the system matrices, the second-order form of the descriptor model is modified to give a full-order model which is proven to be stability-preserving under one-sided projection methods. A coupled vibro-acoustic system is experimentally presented which demonstrates that the proposed methodology can provide a stable reduced order model and allows the full field estimation of the pressure in the presence of frequency-dependent boundary conditions."

# Summary. An optional shortened abstract.
summary: 'Keywords: Vibro-acoustics; Finite element method; Time-domain admittance boundary condition; Model order reduction; Virtual sensing'

tags:
- Source Themes
featured: false

links:
 - name: "Full Paper"
   url: "https://www.sciencedirect.com/science/article/pii/S0888327023007550"
url_pdf: ''
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
  caption: ''
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
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

# {{% callout note %}}
#Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
