---
title: Firm non-expansive mappings in weak metric spaces 
authors:
- me
- Cormac Walsh

date: "2022-05-21T00:00:00Z"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "Archiv der Mathematik"
  volume: 119
  issue: 4
  pages: 389--400

peer_reviewed: true
open_access: true
#license: CC-BY-4.0

abstract: We introduce the notion of firm non-expansive mapping in weak metric spaces, extending previous work for Banach spaces and certain geodesic spaces. We prove that, for firm non-expansive mappings, the minimal displacement, the linear rate of escape, and the asymptotic step size are all equal. This generalises a theorem by Reich and Shafrir.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Metric Functionals
- Firm Mappings
- Nonexpansive Mappings
- Weak Metrics
- Fixed Points

featured: true

hugoblox:
  ids:
    doi: "10.1007/s00013-022-01759-5"
    arxiv: "2110.13195"

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

We introduce **firm non-expansive mappings** in arbitrary weak metric spaces, extending the classical notion beyond Banach spaces and geodesic metric spaces.

### 1. Equality of asymptotic quantities

Our main theorem establishes that, for every firm non-expansive mapping \(T:X\to X\) on a weak metric space \((X,\delta)\), every \(x\in X\), and every integer \(k\geq 1\),

\[\begin{aligned} \inf_{y\in X}\delta(y,Ty) &= \lim_{n\to\infty}\frac{\delta(x,T^n x)}{n} \\ &= \lim_{n\to\infty}\delta(T^n x,T^{n+1}x) \\ &= \frac{1}{k}\lim_{n\to\infty}\delta(T^n x,T^{n+k}x). \end{aligned}\]

Thus, the **minimal displacement**, **linear rate of escape**, and **asymptotic step size** coincide. This generalizes the Reich–Shafrir theorem without requiring a linear or geodesic structure.

### 2. Metric functionals and zero escape rate

If \(T\) is a firm non-expansive mapping of a metric space with zero linear escape rate, then there exists a metric functional \(h\) such that

\[h(Tx)\leq h(x)\qquad\text{for every }x\in X.\]

Consequently, \(h\) is non-increasing along every orbit of \(T\).

### 3. Monotone escape in finite-dimensional normed spaces

If \(T\) is a firm non-expansive mapping of a finite-dimensional normed space with zero linear escape rate, then **either** \(T\) has bounded orbits **or** there exists a metric functional \(h\) such that

\[h(T^n x)\longrightarrow -\infty\qquad\text{monotonically, for every }x.\]

Moreover, \(h\) can be chosen as a limit point of the orbit \((T^n0)_{n\geq 0}\).

### 4. A broader class of mappings

We show that this notion includes classical firmly non-expansive mappings in Banach spaces and \(W\)-hyperbolic spaces, while also admitting mappings that are not firmly non-expansive in the classical sense. We additionally characterize firmness for non-expansive mappings on one-dimensional asymmetric normed spaces.
