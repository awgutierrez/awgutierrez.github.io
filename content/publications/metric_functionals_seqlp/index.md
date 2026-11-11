---
title: On the Metric Compactification of Infinite Dimensional \(\ell_p\) Spaces
authors:
  - me

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2018-12-28T00:00:00Z"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "Canadian Mathematical Bulletin"
  volume: 62
  issue: 3
  pages: 491--507

peer_reviewed: true
open_access: true
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

abstract: The notion of metric compactification was introduced by Gromov and later rediscovered by Rieffel. It has been mainly studied on proper geodesic metric spaces. We present here a generalization of the metric compactification that can be applied to infinite dimensional Banach spaces. Thereafter we give a complete description of the metric compactification of infinite dimensional \(\ell_p\) spaces for all \(1\leq p < \infty\). We also give a full characterization of the metric compactification of infinite dimensional Hilbert spaces.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Metric Functionals
- Metric Spaces
- Metric Compactification
- Banach Spaces
- Hilbert Spaces

featured: true

hugoblox:
  ids:
#    doi: 
    arxiv: "1802.04710"

links:
  - type: custom
    label: doi
    url: https://www.cambridge.org/core/journals/canadian-mathematical-bulletin/article/on-the-metric-compactification-of-infinitedimensional-ell-p-spaces/BA73E83FEC3E2E7BD7215211C5005EC3
#  - type: custom
#    label: arxiv
#    url: https://arxiv.org/pdf/1802.04710  
 # - type: code
 #   url: https://github.com/HugoBlox/kit
 # - type: dataset
 #   url: ""
 # - type: poster
 #   url: ""
 # - type: project
 #   url: ""
 # - type: slides
 #   url: https://www.slideshare.net/
 # - type: source
 #   url: ""
 # - type: video
 #   url: ""

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

We characterize all metric functionals on infinite-dimensional \(\ell_p\) spaces, \(1\leq p<\infty\).

> [!SUCCESS] Metric functionals on \(\ell_1\)
>
> \[ h(x)=\sum_{i\in I}\sigma_i x_i+\sum_{i\notin I}\bigl(|x_i-a_i|-|a_i|\bigr), \]
>
> where \(I\subseteq\mathbb N\), \(\sigma_i\in\{-1,1\}\) for \(i\in I\), and \(a_i\in\mathbb R\) for \(i\notin I\).
>
> The internal functionals correspond to \(I=\varnothing\) and \(a\in\ell_1\).

> [!SUCCESS] Metric functionals on \(\ell_p\) with \(1 < p <\infty\)
>
> \[ h(x)=\left(\|x-a\|_p^p+c^p-\|a\|_p^p\right)^{1/p}-c, \]
>
> where \(a\in\ell_p\) and \(c\geq\|a\|_p\,\), or
> \[ h(x)=-\langle u,x\rangle, \]
> where \(u\in\ell_q\,\), with \(\,\|u\|_q\leq1\,\) and \(\,pq=p+q\).
>
> The internal functionals correspond to \(c=\|a\|_p \) in the first family.
