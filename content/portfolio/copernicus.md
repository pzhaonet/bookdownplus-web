---
image: img/portfolio/copernicus.png
title: copernicus
weight: 1
---

Write academic papers of Copernicus journals. Support both the two-columned pdf version and the discussion version.

> by Peng Zhao (demo: [pdf](https://github.com/pzhaonet/bookdownplus/raw/master/inst2/copernicus/showcase/copernicus.pdf), [zip](https://github.com/pzhaonet/bookdownplus/raw/master/inst/templates/copernicus.zip))

<!--more-->

Copernicus Publications is a publisher of scientific literature which publishes around 40 peer-reviewed open access scientific journals and other publications on behalf of the European Geosciences Union (EGU). Many years ago, one of my manuscripts was submitted to the academic *Biogeosciences* (BG). I wrote it with LaTeX. BG is one of the top journals in my research area. I believe I will submit to BG again in the future and I would not use LaTeX again. Therefore I created the bookdown template for Copernicus.

Copernicus journal papers are open-access. A submitted manuscript, if accepted, is firstly published online as a discussion version, the layout of which is easy for computer monitors. After successful discussions, the manuscript is published in a two-column printed version:

Copernicus provides a [LaTeX template](https://publications.copernicus.org/for_authors/latex_instructions.html) which is free for using. I modified it as 'tex/template_article.tex', i.e. something was moved from the original LaTeX template to the yaml of 'index.Rmd'. Users could simply compare them and then get an idea how to convert a LaTeX template into a bookdown template.

Here is a brief description for re-use:

- Install R and RStudio.
- Install R bookdown package and R bookdownplus package.
- Create a skeleton of the manuscript.
- Revise the .Rmd files as your own.
- Build the book.

More detals could be found [here](https://github.com/pzhaonet/bookdownplus).
[![](https://github.com/pzhaonet/bookdownplus/raw/master/inst2/copernicus/showcase/copernicus2.png)](https://github.com/pzhaonet/bookdownplus/raw/master/inst2/copernicus/showcase/copernicus2.png)
[![](https://github.com/pzhaonet/bookdownplus/raw/master/inst2/copernicus/showcase/copernicus3.png)](https://github.com/pzhaonet/bookdownplus/raw/master/inst2/copernicus/showcase/copernicus3.png)
[![](https://github.com/pzhaonet/bookdownplus/raw/master/inst2/copernicus/showcase/cover.png)](https://github.com/pzhaonet/bookdownplus/raw/master/inst2/copernicus/showcase/cover.png)

