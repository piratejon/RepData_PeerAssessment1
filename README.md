About
=====
This repo is a fork of https://github.com/rdpeng/RepData_PeerAssessment1 for Coursera Data Science Reproducing Research

Instructions
============
First you must obtain the data from https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip which is provided in the repo as activity.zip. This zip file must be extracted, the result of which is contained in this repository as activity.csv. (Note: no action is required; the input file is already downloaded, extracted, and included to this repo.)

The output file (PA1_template.html and supporting figures) has already been constructed and included in this repo; it could be re-built with the following R code:
```{r}
require{knitr}
knit2html('PA1_template.Rmd', 'PA1_template.html')
```

The intermediate file, PA1_template.md, is also included.

