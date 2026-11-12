---
title: Subinvariant Metric Functionals for Nonexpansive Mappings 
authors:
- me
- Olavi Nevanlinna

date: "2025-06-26T00:00:00Z"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "Numerical Functional Analysis and Optimization"
  volume: 46
  issue: 8-9
  pages: 725--742

peer_reviewed: true
open_access: true
#license: CC-BY-4.0

abstract: We investigate the existence of subinvariant metric functionals for commuting families of nonexpansive mappings in noncompact subsets of Banach spaces. Our findings underscore the practicality of metric functionals when searching for fixed points of nonexpansive mappings. To demonstrate this, we additionally investigate subsets of Banach spaces that have only nontrivial metric functionals. We particularly show that in certain cases every metric functional has a unique minimizer; thus, subinvariance implies the existence of a fixed point.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Metric Functionals
- Subinvariance
- Nonexpansive Mappings
- Banach Spaces
- Minimizers
- Fixed Points

featured: true

hugoblox:
  ids:
#    doi: "https://www.tandfonline.com/eprint/S7JKNW7NQYNZI7FHMXYX/full?target=10.1080/01630563.2025.2528908#d1e195"
    arxiv: "2407.04234"

links:
  - type: custom
    label: DOI
    url: "https://www.tandfonline.com/eprint/S7JKNW7NQYNZI7FHMXYX/full?target=10.1080/01630563.2025.2528908#abstract"
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

We study **common subinvariant metric functionals** for commuting families of nonexpansive mappings on Banach spaces, without imposing compactness assumptions. We also investigate conditions under which subinvariant metric functionals yield fixed points and examine the geometry of metric functionals on Banach spaces.

### 1. Common subinvariant metric functionals for affine mappings

**Theorem 3.1.** Let \(E\) be a Banach space and \(\mathcal{F}\) a commuting family of affine nonexpansive mappings on \(E\). Suppose \(X\subseteq E\) is nonempty and convex, and that every \(T\in\mathcal{F}\) satisfies

\[T(X)\subseteq X,\qquad \inf_{x\in X}\|x-Tx\|=0.\]

Then there exists a metric functional \(h\in X^\diamondsuit\) such that

\[h(Tx)\leq h(x)\qquad\text{for all }x\in E,\ T\in\mathcal{F}.\]

Thus, the entire commuting family admits a **common subinvariant metric functional**, even when \(X\) is not compact.

### 2. Extension to general nonexpansive mappings

**Theorem 3.3.** We extend the existence result to commuting families of nonexpansive mappings without assuming affinity or convexity.

More precisely, let \(\mathcal{F}\) be a commuting family of nonexpansive mappings on a Banach space \(E\), and let \(X\subseteq E\) be nonempty and invariant under every mapping in \(\mathcal{F}\). If there exists \(x_0\in X\) such that, for every \(T\in\mathcal{F}\),

\[\lim_{n\to\infty}\|T^n x_0-T^{n+1}x_0\|=0,\]

then there exists a metric functional \(h\in X^\diamondsuit\) satisfying

\[h(Tx)\leq h(x)\qquad\text{for all }x\in E,\ T\in\mathcal{F}.\]

### 3. A fixed-point theorem using the Opial property

**Theorem 3.6.** Let \(X\) be a nonempty weakly compact subset of a Banach space having the **Opial property**. If a mapping \(T:X\to X\) admits a subinvariant metric functional \(h\in X^\diamondsuit\), then \(T\) has a fixed point in \(X\).

Notably, **nonexpansiveness of \(T\) is not required** in this theorem.

This result connects the existence of subinvariant metric functionals with fixed-point theory through the geometry of the underlying Banach space.

### 4. Metric functionals associated with rays

**Proposition 4.12.** Suppose \(X\) contains a ray \(\{tu:t\geq 0\}\), where \(\|u\|=1\). Then the limit

\[h(x)=\lim_{t\to\infty}(\|x-tu\|-t)\]

defines a metric functional in \(X^\diamondsuit\), and

\[h(su)=-s\qquad\text{for every }s\geq 0.\]

In particular, \(h\) is unbounded below. We also express this functional in terms of the subdifferential of the norm:

\[h(x)=\max\{-\langle x,f\rangle:f\in\partial\|\cdot\|(u)\}.\]

### 5. Metric functionals on uniformly smooth Banach spaces

**Theorem 4.16.** If \(E\) is uniformly smooth, every metric functional arising from a net escaping to infinity is a continuous linear functional of norm at most one.

Conversely, every continuous linear functional of norm at most one can be obtained as a pointwise limit of metric functionals associated with points of \(E\).

This provides a characterization of the metric functionals arising at infinity in uniformly smooth Banach spaces.


### 6. Nontrivial metric functionals and the zero-free property

We introduce the **zero-free property (ZFP)**: a metric space \(X\) has ZFP if none of its metric functionals vanishes identically.

We establish several results describing when this property holds:

- **Proposition 4.17.** The Banach space \(B(S)\) of bounded real-valued functions on any nonempty set \(S\), equipped with the supremum norm, has ZFP.
- **Proposition 4.18.** If \(K\) is a compact Hausdorff space, then \(C(K)\), equipped with the supremum norm, has ZFP.
- **Proposition 4.20.** If a Banach space \(E\) has the Radon–Riesz property and its closed unit ball \(B_E\) is weakly compact, then \(B_E\) has ZFP.

We also investigate how ZFP behaves under direct sums and changes of metric, showing that it depends on the geometry of the underlying metric space.

### 7. Unique minimizers of metric functionals

We introduce the **unique minimizer property (UMP)**: a metric space \(X\) has UMP if every metric functional \(h\in X^\diamondsuit\) attains its minimum at exactly one point of \(X\).

**Proposition 4.22.** If \(E\) is a Banach space with the Opial property and \(X\subseteq E\) is nonempty and weakly compact, then \(X\) has UMP.

Consequently, every metric functional \(h\in X^\diamondsuit\) has a unique minimizer \(a\in X\):

\[h(a) < h(x)\qquad\text{for all }x\in X\setminus\{a\}.\]

**Proposition 4.25.** Let \(X\) be a bounded subset of a uniformly convex Banach space \(E\). If a sequence \((a_n)\subseteq X\) generates a metric functional \(h\in X^\diamondsuit\), then \(h\) has a unique minimizer in \(E\), although this minimizer need not belong to \(X\).

These results explain how the geometry of Banach spaces can turn the existence of subinvariant metric functionals into fixed-point information. In particular, when \(X\) has UMP and \(h\in X^\diamondsuit\) is subinvariant under \(T:X\to X\), the unique minimizer of \(h\) must be a fixed point of \(T\).

### 8. Examples in classical sequence spaces

We investigate the affine shift

\[T(x_1,x_2,\ldots)=(1,x_1,x_2,\ldots)\]

on several classical sequence spaces.

The examples reveal substantially different behavior: on \(\ell_2\), the only subinvariant metric functional for this mapping is the zero functional, whereas on \(\ell_1\) there are infinitely many nontrivial subinvariant metric functionals.

For instance, on \(\ell_1\),

\[h(x)=\sum_{k=1}^{\infty}(|x_k-1|-1)\]

satisfies

\[h(Tx)=h(x)-1.\]

These examples illustrate how the geometry of the ambient Banach space influences the structure and usefulness of subinvariant metric functionals.


