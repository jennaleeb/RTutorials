---
title       : Introduction to R
subtitle    : 
author      : Jenna Blumenthal
job         : MIE 1402
framework   : deckjs        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

--- .intro-slide

## Introduction to R

   **Jenna Blumenthal**  
   MIE 1402

---

## What is R?

- Language & environment for statistical computing
- Widely used by statisticians, data miners
- Popular among academics & industry

---

## What is it used for?

- Data handling, organizing
- Basic mathematical operations
- Linear, nonlinear modeling, classical stats tests, time-series analysis, classification, clustering, etc
- Publication-quality graphics

---

## What makes R so great?

- Open source (i.e. free)
- Highly extensible (user-submitted **packages**)
  + Functions available for very specific areas
- Excellent documentation
- Great graphics
  + Publication-quality graphs (`ggplot2`)
  + RMarkdown, LaTeX (write reports without copying and pasting)
  + Shiny (interative data visualizations, etc.)
- Reproducible analysis

---

## What are some other options?

- SAS, SPSS, Stata, MATLAB, etc...
- Not so free
- Not so open-source (meaning there is a smaller community to help when you get stuck)

---

## Getting set up

### What you'll need

R: [http://www.r-project.org/](http://www.r-project.org/)

### What you'll want
RStudio (highly recommended GUI): [https://www.rstudio.com/](https://www.rstudio.com/)

LaTeX (good for report-writing): [https://www.latex-project.org/](https://www.latex-project.org/)

Git (good for version control): [https://git-scm.com/downloads](https://git-scm.com/downloads)

---

## RStudio

![](assets/img/RStudio_screenshot.png)

---

### Console
- Command-line interface
- Type after the `>` prompt and R will execute your command
- This is where R does the stuff
  
### Editor
- Collection of commands can be edited and saved
- `File --> New | File --> Open --> R Script`
  
### Environment
- What data/values R has in its memory
- Good for viewing complex objects
  
### Files, packages, docs, views
- Browse directory, open files, install/load packages, look at documentation (for help), preview graphs, etc.


---

## Getting started

Before you start being a stats wizard...get organized.

---

### 1. Working directory

- The folder you are currently in
- If you ask R to retrieve a certain file, it will look in the working directory (unless another path is given)
- If you save a file from R, it will save in your working directory (ditto)
- Be careful, sometimes you think you are in the correct wd, but you are not. Double check using:
  

```r
getwd()
```

You can change the working directory using 


```r
setwd("Desktop/ExperimentalMethods/RTutorials")
```

---

### 2. Install packages/load libraries

- The core of what makes R great
- Some useful ones come preloaded, but there are many more
- Andy Field will reference the ones he uses in the textbook



```r
install.packages("package-name")
library(package-name)
```

#### Notes

- The first one uses quotes, the second doesn't. Don't ask me why.
- Often you figure out you don't have a package by getting an error.
- Check to see what packages you have installed using

```r
library()
```
- You only have to **install** the package once, but you need to **load** the package every time you set up a new environment.

---

## Some basic examples


```r
1+1
```

```
## [1] 2
```


```r
a = 4
a
```

```
## [1] 4
```


---

## Data

import()
using data from package

---

## Viewing , summarizing, ec

--- 

## Basic math

---

## Simple graph

(can mention ggplot coming soon)

---

## Saving/workflow

---

## References

Wikipedia:
[https://en.wikipedia.org/wiki/R_(programming_language)](https://en.wikipedia.org/wiki/R_(programming_language))

A (very) short introduction to R: 
[https://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf](https://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf)

---






