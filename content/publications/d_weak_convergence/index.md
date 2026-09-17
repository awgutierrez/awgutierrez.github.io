---
title: Metric Functionals and Weak Convergence 
authors:
- me
- Olavi Nevanlinna

date: "2026-04-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "Zeitschrift für Analysis und ihre Anwendungen"
 # volume: 155
 # issue: 1
 # pages: 51--65

peer_reviewed: true
open_access: true
#license: CC-BY-4.0

abstract: "We introduce a notion of weak convergence in arbitrary metric spaces. Metric functionals are key in our analysis: weak convergence of sequences in a given metric space is tested against all metric functionals defined on said space. When restricted to bounded sequences in normed linear spaces, we prove that our notion of weak convergence agrees with the standard one."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Metric Functionals
- Weak Convergence
- Metric Spaces
- Normed Spaces

featured: true

hugoblox:
  ids:
    doi: "10.4171/ZAA/1828"
    arxiv: "2506.04154"

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

> [!info] Metric Functionals

Given a metric space \((X,d)\), pick a point \(o\in X\) 
and define the set 
 \[ X^\vee := \{x \mapsto d(x,w)-d(o,w) \mid w\in X\}. \]
Denote by \(X^\diamondsuit\) the closure of \(X^\vee\) 
in the topology of pointwise convergence. We call each element 
in \(X^\diamondsuit\) a _metric functional_.
Note that every metric functional is a \(1\)-Lipschitz map \(X\to\mathbb{R}\)
that vanishes at the point \(o\).

> [!info] Weak Convergence in Metric Structures

***Definition***
Let \((X,d)\) be a metric space and \(X^\diamondsuit\) the space of all
metric functionals on \(X\). We say that a sequence \((a_n)\) in \(X\)
converges \(d\)-weakly to \(a\in X\) if for every \(\mathbf{h}\in X^\diamondsuit\)
we have
\[ \liminf_{n\to\infty}\, \mathbf{h}(a_n) \geq \mathbf{h}(a).\] 

> [!success] Behavior in Linear Worlds seen with Metric Eyes

***Theorem***
A bounded sequence in a normed linear space converges \(d\)-weakly
if and only if it converges in the classical weak sense.

> [!important] Can unbounded sequences converge \(d\)-weakly?

Yes. For example, if \(X\) is the real line equipped with
the metric 
\[ d(x,y)=\sqrt{|x-y|},\] 
we have \(X^\diamondsuit = X^\vee\cup\{0\}\)
and the unbounded sequence \(a_n=n\) converges \(d\)-weakly to every
point in \(X\).

***Theorem***
If \(X\) is the space \(\ell_1\) or is a normed linear space whose dual space
is strictly convex, then \(d\)-weakly convergent sequences are bounded.

> [!warning] There is an error in Theorem 1.4 in the printed version.
> The space \(C[0,1]\) does not have the claimed property. 
> [Check this out](../weak_topology/index.md).



