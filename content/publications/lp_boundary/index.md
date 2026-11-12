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

## Main results

We characterize all horofunctions on finite-dimensional \(\ell_p^n\) spaces, with \(1\leq p\leq\infty\), and for Hilbert's projective metric.

### 1. Horofunctions on \(\ell_1^n\)

\[ h(x)=\sum_{i\in I}\sigma_i x_i+\sum_{i\notin I}\bigl(|x_i-a_i|-|a_i|\bigr), \]

where \(\varnothing\neq I\subseteq[n]\), \(\sigma_i\in\{-1,1\}\), and \(a_i\in\mathbb R\).

### 2. Horofunctions on \(\ell_p^n\), \(1 < p <\infty\)

\[ h(x)=-\langle u,x\rangle,\qquad \|u\|_q=1,\qquad \frac1p+\frac1q=1. \]

### 3. Horofunctions on \(\ell_\infty^n\)

\[ h(x)=\max\left\{\max_{i\in I}(x_i-a_i),\max_{j\in J}(-x_j-b_j)\right\}, \]

where \(I,J\subseteq[n]\) are disjoint, \(I\cup J\neq\varnothing\), and \(a_i,b_j\geq0\) satisfy

\[ \min\bigl(\min_{i\in I}a_i,\min_{j\in J}b_j\bigr)=0. \]

Here, \(\min\varnothing=\infty\) and \(\max\varnothing=-\infty\).

### 4. Horofunctions for Hilbert's projective metric on \(\mathbb R_{>0}^n\)

\[ h(x)=\log\left(\max_i u_i x_i\right)+\log\left(\max_j\frac{v_j}{x_j}\right), \]

where \(u,v\in [0,\infty)^n \) satisfy

\[ \|u\|_\infty = \|v\|_\infty=1,\qquad u_i v_i=0\quad(\forall i). \]
