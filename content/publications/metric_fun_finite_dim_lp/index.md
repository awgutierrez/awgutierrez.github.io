---
title: The Horofunction Boundary of Finite Dimensional \(\ell_p\) Spaces 
authors:
- me
#- Robert Ford
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
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

peer_reviewed: true
#open_access: true
#license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
# Note: a Test of Time award years after publication uses an explicit `date` that differs from the page date.
#awards:
#  - name: "Test of Time Award"
#    level: winner
#    date: "2025"
#    note: "Awarded for sustained impact 10 years after publication."
#  - name: "Editor's Choice"
#    level: featured

#funding:
#  - funder: "National Science Foundation"
#    grant: "NSF-1234567"

abstract: We give a complete description of the horofunction boundary of finite dimensional \(\ell_p\) spaces for \(1\leq p \leq \infty\). We also study the variation norm on \(\mathbb{R}^n\), and the corresponding horofunction boundary. As a consequence, we describe the horofunctions for Hilbert's projective metric on the interior of the standard cone \(\mathbb{R}_{+}^n\) of \(\mathbb{R}^n\).

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Metric Functionals

featured: true

hugoblox:
  ids:
    arxiv: 1709.03462

links:
  - type: custom
    label: DOI
    url: https://doi.org/10.4064/cm7320-3-2018
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
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

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

> [!success] Metric functionals on \(\ell_1^n\)
> Every metric functional on \(\ell_1^n\) is either internal or of the form
$$ h(x) = \sum_{i\in I}\epsilon_i x_i + \sum_{i\not\in I}(|x_i - \mu_i| - |\mu_i|),$$
> where \(\empty \neq I \subseteq [n]\), \((\epsilon_i) \in \{-1, 1\}^I\), and 
\((\mu_i) \in \mathbb{R}^{[n]\setminus I}\).

> [!success] Metric functionals on \(\ell_p^n\) with \(1 < p < \infty\)
> Every metric functional on \(\ell_p^n\) with \(1 < p < \infty\) is either internal
> or of the form 
$$ h(x) = - \sum_{i\in [n]} \mu_i x_i\,,$$
> where \((\mu_i)\in \mathbb{R}^n\) with \(||\mu||_{q} = 1\) and \(q :=p(p-1)^{-1}\).
