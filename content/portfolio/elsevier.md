---
image: img/portfolio/elsevier.png
title: elsevier
weight: 1
---

Write academic papers of Elsevier journals.

> by Peng Zhao (demo: [pdf](https://github.com/pzhaonet/bookdownplus/raw/master/inst2/elsevier/showcase/elsevier.pdf), [zip](https://github.com/pzhaonet/bookdownplus/raw/master/inst/templates/elsevier.zip))

<!--more-->


One of my academic manuscripts, published on *Agricultural and Forest Meteorology*, was the first paper of mine written in R bookdown environment from the preparation to the publication. Hooray! 

Elsevier is one of the world's major providers of scientific, technical, and medical information. Elsevier owns  2500 journals, which is why I would like to share my bookdown manuscript for re-use.

Elsevier provides a [LaTeX template](https://www.elsevier.com/authors/author-schemas/latex-instructions) which is free for using. I modified it as 'tex/template.tex', i.e. something was moved from the original LaTeX template to the yaml of 'index.Rmd'. Users could simply compare them and then get an idea how to convert a LaTeX template into a bookdown template.

Install R, bookdown, LaTeX, and bookdownplus. Then run the following code in R language to create a book from this template:

```r
library('bookdownplus')
bd('elsevier')
```

More detals could be found [here](https://github.com/pzhaonet/bookdownplus).
<p><a href="https://github.com/pzhaonet/bookdownplus/raw/master/inst2/elsevier/showcase/cover.png"><img class = "jf-image-shadow" src="https://github.com/pzhaonet/bookdownplus/raw/master/inst2/elsevier/showcase/cover.png" /></a></p>
<p><a href="https://github.com/pzhaonet/bookdownplus/raw/master/inst2/elsevier/showcase/elsevier2.png"><img class = "jf-image-shadow" src="https://github.com/pzhaonet/bookdownplus/raw/master/inst2/elsevier/showcase/elsevier2.png" /></a></p>
