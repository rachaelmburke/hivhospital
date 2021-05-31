---
title: "TB COVID Blantyre"
author: "R Burke"
date: "08/03/2021"
output: html_document
---

This is a companion website (and github repository) to our analysis of HIV related hospital admissions to QECH.  It's purpose is to share code (and some data) with scientific community.

On the website (https://rachaelmburke.github.io/hivhospital/) you can see knitted code containing output and code for all the analyses in the paper.

The github repo contains the following relevant folders:

1. Data -- contains real data on Blantyre population from Blantrye census (files 'blantyre_cenus_by_q.rda' and 'cens_edit.rda'). This also contains two "synthetic" (artificial) datasets for spine analyes; pre- and post- imputation.
2. Code -- contains Rmd files for the real analyses, the supplementary material and a slightly tweaked Rmd file that will run with included data.
3. Knitted -- contains the above Rmd files but knitted to .html
4. Figures -- contains pdfs of all figures and supplementary figures in the paper.

The synthetic datasets were created using "synthpop" package in R.  They are designed to facilitate understanding of our code and analysis but are not suitable for running accurate further analysis. See Nowok, B., Raab, G. M. & Dibben, C. synthpop: Bespoke Creation of Synthetic Data in R. Journal of Statistical Software 74, 1–26 (2016) for more detail.

Further information about the analyses / SPINE project is available by contacting the first or last authors (rachael.burke@lshtm.ac.uk or peter.macpherson@lstmed.ac.uk). Data requests for the real dataset can also be directed to MLW data department (data@mlw.mw) who may be able to facilitate data sharing, permission from QECH may be required.