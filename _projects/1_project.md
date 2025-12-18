---
layout: page
title: Semiorthogonal decomposition of stable $\infty$-categories.
description: Work in progress, advised by [Prof. Dr. Tobias Dyckerhoff](https://www.math.uni-hamburg.de/home/dyckerhoff/).
img: assets/img/beilinsonsod_img.jpg
importance: 1
category: work
related_publications: false
---

Semiorthogonal decompositions of triangulated categories, first introduced by Bondal & Kapranov in 1989, have been a central tool in the study of derived categories for a long time. They give a systematic way to divide triangulated categories, e.g. the derived category $D^b(X)$ of coherent sheaves on an algebraic variety $X$ (or more generally a noetherian scheme), into simpler pieces. Perhaps most importantly, a semiorthogonal decomposition of a triangulated category $\mathcal T$ yields a direct sum decomposition of its $K$-theory $K(\mathcal T)$.

A natural (but vague) question in this context is the following: Given a semiorthogonal decomposition $\langle \mathcal A_0, \dots, \mathcal A_n \rangle$ of $\mathcal T$, what is a natural condition to impose so that $\mathcal T$ is reconstructible from the subcategories $\mathcal A_0, \dots, \mathcal A_n$ together with some form of gluing data? It turns out that if all of the inclusions of the subcategories $\mathcal A_0, \dots, \mathcal A_n$ admit left adjoints, then the subcategories form a lax $n$-simplex, i.e. a strictly unitary lax functor $[n] \to \mathcal Cat$ into the $2$-category of (small) categories. One would hope that $\mathcal T$ is then determined by this lax functor. However, essentially due to the non-functoriality of the cone, a calculation to reconstruct $\mathcal T$ fails.

Luckily, as shown as part of this work, this defect disappears in the enhanced setting of stable $\infty$-categories, a generalization of triangulated categories introduced by Lurie (2006). We develop an analogous "enhanced" theory of semiorthogonal decompositions of length $n$ in this context, extending the approach of Dyckerhoff & Kapranov (2021) for length $1$. As a preliminary result, we give a direct proof of an equivalence of $\infty$-categories between Waldhausen diagrams and coherent complexes valued in a stable $\infty$-category $\Euscript C$.

An early draft of this project, which turned into my Bachelor thesis, is available below. At the moment, I am trying approach the stated reconstruction theorem more rigorously, possibly using the language of $\infty$-bicategories. Eventually, I plan to analyze mutation functors in this setting.
