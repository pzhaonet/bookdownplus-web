+++
date = "2018-09-23T21:05:33+05:30"
title = "About"
+++

### The Story

Many years ago, I collected some LaTeX templates when learning LaTeX. However, my interest in LaTeX was gone after submitting my PhD dissertation. I should have deleted these templates if they had not been so small. They would never be useful in the future, I thought.

In 2017, I started writing the book [*Learning R: R for Rookies*](https://xuer.pzhao.org). Unexpectedly, MS Word could not satisfy me with the typesetting. You know what I mean if you have experience (and pain) in writing a long book or dissertation with Word. Actually I suffered more, but I do not want to talk about it. I was sure that LaTeX could, but I would rather not use it. 

Like a bolt out of the blue, I found [bookdown](https://CRAN.R-project.org/package=bookdown).

From then on, I could not help spending time on this amazing tool. My book was completed with bookdown. My manuscripts, produced by bookdown, were submitted to academic journals and accepted. I wrote my papa-and-son diaries on bookdown.org. All the LaTeX templates were brought back to life: I packed them in an R package: [bookdownplus](http://www.pzhao.org/en/post/bookdownplus-released/).

Bookdownplus was supppsed to be a shortcut to bookdown. In the recently year, I have been doing my best to provide the beginners (and me) a friendly way to using bookdown. However, I struggled with two annoying problems. The first one is how the users (including me) can easily choose the right template. The second one is how the users (including me) can easily contribute their own templates to bookdownplus.

[This web app](https://bookdownplus.netlify.com) you are viewing now is intended to solve these problems. Users can search for elegant bookdown templates of interest, download the template package, and leave their comments. Furthermore, contributors' templates, if submitted to the [bookdownplus repository](https://github.com/pzhaonet/bookdownplus), can view their templates on this website as soon as possible.

In another word, this web app is a showcase of the R bookdownplus package, or a window of bookdown templates. 

### What is bookdownplus?

[bookdownplus](https://CRAN.R-project.org/package=bookdownplus) is an open-source software package that helps users write many kinds of books and articles, including academic journal articles, theses and dissertations, programming books (especially in R language), even guitar books, chemical equations, mails, calendars, and diaries. bookdownplus works on the basis of [bookdown](https://github.com/rstudio/bookdown).

### What is bookdown?

bookdown is an open-source package that facilitates writing books and long-form articles/reports. It can generate printer-ready books and ebooks with multiple choices of output formats such as PDF, LaTeX, HTML, EPUB, and Word. bookdown stands on the shoulder of R Markdown. 

### What is R and what is Markdown?

[R](https://en.wikipedia.org/wiki/R_(programming_language)) is an open source programing language. [Markdown](https://en.wikipedia.org/wiki/Markdown) is a lightweight markup language with plain text formatting syntax. [R Markdown](https://rmarkdown.rstudio.com/) is a combination of both, and more.

### Complicated?

Well, it sounds complicated so far, but it actually isn't. 

You don't have to know the definitions of R, Markdown or bookdown. Just move on and use it, and you will learn what they are. bookdownplus helps. Following the quick start on the [bookdownplus repo](https://github.com/pzhaonet/bookdownplus), you can create a demo book (or multiple demo books) in .pdf or .doc, or even more formats with just one single command. Full documentation can be found in the book [R bookdownplus Textbook](https://bookdown.org/baydap/bookdownplus).

You don't know which template to choose? The home page of this website is a gallery of them, each with a title of the template name.


### Share your own templates

If you are willing to share your bookdown templates, just upload them to the [bookdownplus repo](https://github.com/pzhaonet/bookdownplus). They will be displayed in the gallery automatically once accepted.

From the version 1.5, bookdownplus opens a widest-ever door to contributors. Here is how:

1. Make sure that your template works successfully with bookdown.
2. Prepare a folder in your working directory by running `bookdownplus::share('your_template_name')` . Follow the instructions in each subfolder and create the required files. 
  - (Mandatory) 'your_template_name/demo.zip' is the compressed file from your bookdown project folder.
  - (Optional) 'your_template_name/showcase/' contains the sample files (e.g. pdf, image files). An image file 'cover.png' is recommended, which will be used as the cover image in the gallery.
  - (Optional) You could write a 'your_template/readme.txt' (in markdown syntax), which will be displayed as the text in the gallery.
3. Upload your template folder 'your_template_name/' in to '[upload/](https://github.com/pzhaonet/bookdownplus/tree/master/upload)' of the bookdownplus repo. 
4. Add the template information, including the template name, the contributor's name, and a brief introduction, into 'upload/-list.csv'.
5. Create a Pull Request to bookdownplus.

Wait for the response, and your template will be available in the gallery. R users can get it easily by clicking the ".zip" link in the gallery, or running

```
bookdownplus("your_template_name")
```

Any suggestions? Please [contact me](https://bookdownplus.netlify.com/contact/)!