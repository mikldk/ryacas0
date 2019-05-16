# `Ryacas0`: Legacy version of `Ryacas` #

[![Build Status](https://travis-ci.org/mikldk/ryacas0.svg?branch=master)](https://travis-ci.org/mikldk/ryacas0)
[![Build status](https://ci.appveyor.com/api/projects/status/21ffy6m7scx92ctk?svg=true)](https://ci.appveyor.com/project/mikldk/ryacas0/branch/master)


`Ryacas0` is a legacy version of [`Ryacas`](https://github.com/mikldk/ryacas).

`Ryacas0` is an [R](https://www.r-project.org/) interface to
the free [yacas](http://www.yacas.org) Computer Algebra
System. `Ryacas0` allows one to send R expressions,
unprocessed yacas strings and certain other R objects to
yacas process from R and get back the result. It also has
facilities for manipulating yacas strings and R expressions
destined for yacas processing.

It can be used for exact arithmetic, symbolic math, ASCII
pretty printing and translating R to TeX. 

## Install from github ##

To build and install from github using R 3.3.0 (or later) and the R devtools package 1.11.0 (or later) run this command from within R:

    devtools::install_github("mikldk/ryacas0")

## Online info ##

For vignettes, overview, pointers to additional information, installation
instructions and a sample session see <http://mikldk.github.io/ryacas0/>. 

Yacas documentation can be found at http://yacas.readthedocs.org/

## More ##

Once `Ryacas0` is installed, pointers to additional information
can be found with these R commands:

    library(Ryacas0)
    package?Ryacas0


## Yacas ##

The package contains stripped-down yacas distribution. For the complete yacas source code see <https://github.com/grzegorzmazur/yacas/> . For more information on yacas see <http://www.yacas.org/>.

---

Mikkel Meyer Andersen, mikl at math dot aau dot dk  
Rob Goedman, goedman at mac dot com  
Gabor Grothendieck, ggrothendieck at gmail dot com  
Søren Højsgaard, sorenh at math dot aau dot dk  
Ayal Pinkus, apinkus at xs4all dot nl  
Grzegorz Mazur, teoretyk at gmail dot com  

