---
layout: page
title: Semiorthogonal decomposition of stable $\infty$-categories.
description: Work in progress, advised by Prof. Dr. Tobias Dyckerhoff.
img: assets/img/beilinsonsod_img.jpg
importance: 1
category: work
related_publications: false
---

Semiorthogonal decompositions of triangulated categories, first introduced by Bondal & Kapranov in 1989, have been a central tool in the study of derived categories for a long time. They give a systematic way to divide triangulated categories, e.g. the derived category $D^b(X)$ of coherent sheaves on an algebraic variety $X$ (or more generally a noetherian scheme), into simpler pieces. Perhaps most importantly, a semiorthogonal decomposition of a triangulated category $\mathcal T$ yields a direct sum decomposition of its $K$-theory $K(\mathcal T)$.

A natural question in this context is the following: Given a semiorthogonal decomposition $\langle \mathcal A_0, \dots, \mathcal A_n \rangle$ of $\mathcal T$,  is $\mathcal T$ reconstructible from the subcategories $\mathcal A_0, \dots, \mathcal A_n$ together with some form of gluing data? In general, this is not possible. But it turns out that if all of the inclusions of the subcategories $\mathcal A_0, \dots, \mathcal A_n$ admit left adjoints, then the subcategories form an oplax $n$-simplex of categories, i.e., there are functors $F_{ij} : \mathcal A_i \to \mathcal A_j$ and a compatible system of natural transformations $\eta_{ijk} : F_{ik} \Rightarrow F_{jk} \circ F_{ij}$. Morally, $\mathcal T$ should be reconstructible from this data. However, this fails as, essentially, the non-functoriality of the cone prevents such a calculation from being possible.

Luckily, as shown as part of this work, this defect disappears in the enhanced setting of stable $\infty$-categories, a generalization of triangulated categories introduced by Lurie (2006). We develop an analogous "enhanced" theory of semiorthogonal decompositions of length $n$ in this context, extending the approach of Dyckerhoff & Kapranov (2021) for length $1$. As a preliminary result, we give a direct proof of an equivalence of $\infty$-categories between Waldhausen diagrams and coherent complexes valued in a stable $\infty$-category $\mathcal C$. The main example coming from algebraic geometry is the classical Beilinson semiorthogonal decomposition of $\mathbb P^n$. We prove an enhanced version of Beilinson's theorem on the derived equivalence between $\text{Coh}(\mathbb P^n)$ and representations of the Beilison quiver, which asserts a reconstruction of the $\infty$-category $D^b(\text{Coh}(\mathbb P^2))$ (and for general $n$) as the oplax limit of the following diagram:

{% include figure.html
   url="/assets/img/beilisonsod_img.jpg"
   caption="Figure 1: Classifying diagram of $D^b(\text{Coh}(\mathbb P^2))$"
   alt="image"
   width="400px"          <!-- or "50%" etc. -->
%}

An early draft of this project turned into my Bachelor thesis. A more polished version will be available on the arXiv soon.