---
title: The Horofunction Boundary of Finite Dimensional \(\ell_p\) Spaces 
authors:
- me

date: "2018-10-19T00:00:00Z"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "Colloquium Mathematicum"
  volume: 155
  issue: 1
  pages: 51--65

peer_reviewed: true
open_access: true
#license: CC-BY-4.0

abstract: We give a complete description of the horofunction boundary of finite dimensional \(\ell_p\) spaces for \(1\leq p \leq \infty\). We also study the variation norm on \(\mathbb{R}^n\), and the corresponding horofunction boundary. As a consequence, we describe the horofunctions for Hilbert's projective metric on the interior of the standard cone \(\mathbb{R}_{+}^n\) of \(\mathbb{R}^n\).

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Metric Functionals
- Horofunctions
- Horofunction Boundary
- Normed Spaces
- Hilbert's Projective Metric

featured: true

hugoblox:
  ids:
    doi: 10.4064/cm7320-3-2018
    arxiv: 1709.03462

links:
#  - type: custom
#    label: DOI
#    url: https://doi.org/10.4064/cm7320-3-2018
#  - type: custom
#    label: arxiv
#    url: https://arxiv.org/pdf/1709.03462  
#  - type: pdf
#    url: 
#  - type: code
#    url: https://github.com/HugoBlox/kit
#  - type: dataset
#    url: ""
#  - type: poster
#    url: ""
#  - type: project
#    url: ""
#  - type: slides
#    url: https://www.slideshare.net/
#  - type: source
#    url: ""
#  - type: video
#    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

params:
  math: true

---

Main results
------------

> [!success] Horofunctions on \(\ell_1^n\)
> \[ h(x) = \sum_{i\in I}\sigma_i x_i + \sum_{i\in [n]\setminus I}(|x_i - \rho_i| - |\rho_i|) \]
> where  
>   + \(I\,\) nonempty subset of \([n]:=\{1,...,n\}\),      
>   + \(\sigma_i \in \{-1, 1\}\,\) for all \(i\in I\),    
>   + \(\rho_i \in \mathbb{R}\,\) for all \(i\in [n]\setminus I\).

> [!success] Horofunctions on \(\ell_p^n\) with \(1 < p < \infty\)
> \[ h(x) = - \sum_{i\in [n]} \mu_i x_i \]
> where 
>   + \(\mu_i \in \mathbb{R}\,\) for all \(i \in [n]\)
>   + \(||\mu||_{q} = 1\) with \(q :=p(p-1)^{-1}\).
