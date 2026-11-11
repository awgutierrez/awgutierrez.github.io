---
title: Characterizing the metric compactification of \(L_p\) spaces by random measures
authors:
- me
date: "2019-06-18T00:00:00Z"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
# Preprints typically have no formal venue; omit `publication` until the work is accepted.
publication:
  name: "Annals of Functional Analysis"
  volume: 11
  issue: 2
  pages: 227--243

peer_reviewed: true
open_access: true
#license: CC-BY-4.0

#funding:
#  - funder: "Wellcome Trust"
#    grant: "WT-219123/Z/19/Z"

abstract: We present a complete characterization of the metric compactification of \(L_p\) spaces for \(1\leq p < \infty\). Each element of the metric compactification of \(L_p\) is represented by a random measure on a certain Polish space. By way of illustration, we revisit the \(L_p\)-mean ergodic theorem for \(1 < p < \infty\), and Alspach’s example of an isometry on a weakly compact convex subset of \(L_1\) with no fixed points.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Metric Functionals
- \(L_p\) Spaces
- Banach Spaces
- Metric Compactification
- Random Measures

featured: true

hugoblox:
  ids:
    doi: "10.1007/s43034-019-00024-1"
    arxiv: "1903.02502"

links:
#- type: code
#  url: https://github.com/HugoBlox/kit
#- type: slides
#  url: https://www.slideshare.net/
#- type: dataset
#  url: "#"
#- type: poster
#  url: "#"
#- type: source
#  url: "#"
#- type: video
#  url: https://youtube.com
#- type: custom
#  label: doi
#  url: https://link.springer.com/article/10.1007/s43034-019-00024-1
#- type: custom
#  label: arxiv
#  url: https://arxiv.org/pdf/1903.02502  
#- type: preprint
#  label: arxiv
#  provider: arxiv
#  id: 1903.02502

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""

params:
  math: true
---

## Main results

We characterize all metric functionals on \(L^p\) spaces over non-atomic standard probability spaces, \(1\leq p<\infty\), using random probability measures.

> [!SUCCESS] Metric functionals on \(L^1\)
>
> \[ h(f)=\mathbb E\left[\int_{\overline{\mathbb R}}\bigl(|f-r|-|r|\bigr)\,d\xi(r)\right], \]
>
> where \(\xi\) is a random probability measure on \(\overline{\mathbb R}=[-\infty,\infty]\), with the integrand extended by \(-f\) at \(+\infty\) and \(f\) at \(-\infty\).
>
> The internal functionals correspond to \(\xi=\delta_g\), with \(g\in L^1\).

> [!SUCCESS] Metric functionals on \(L^p\) with \(1 < p <\infty\)
>
> \[ h(f)=\bigl(A_\xi(f)-A_\xi(0)+c^p\bigr)^{1/p}-c, \]
>
> where \(A_\xi(f)=\mathbb E\left[\int_{\mathbb R}|f-r|^p\,d\xi(r)\right]\), \(\xi\) is a random probability measure on \(\mathbb R\), and \(c^p\geq A_\xi(0)\,\), or
>
> \[ h(f)=-\mathbb E[fu] \]
>
> where \(u\in L^q\,\) with \(\,\|u\|_q\leq1\,\) and \(\,pq=p+q\).
>
> The internal functionals correspond to \(\xi=\delta_g\) and \(c=\|g\|_p\), with \(g\in L^p\).


