# hivhospital

This is a companion website (and github repository) to our analysis of HIV related hospital admissions to QECH.  It's purpose is to share code (and some data) with scientific community.

On the website (https://rachaelmburke.github.io/hivhospital/) you can see knitted code containing output and code for all the analyses in the paper.

The github repo contains the following relevant folders:

1. Data:
    Real data on Blantyre population from Blantrye census (files 'blantyre_cenus_by_q.rda' and 'cens_edit.rda'). 
    Two "synthetic" (artificial) datasets for spine analyes; pre- and post- imputation.
    A csv and rds summary of points in Supplementary Material graphs.
2. Code -- contains Rmd files for the real analyses, the supplementary material and a slightly tweaked Rmd file that will run with included data.
3. Figures -- contains pdfs of all figures and supplementary figures in the paper.

The synthetic datasets were created using "synthpop" package in R.  They are designed to facilitate understanding of our code and analysis but are not suitable for running accurate further analysis. See Nowok, B., Raab, G. M. & Dibben, C. synthpop: Bespoke Creation of Synthetic Data in R. Journal of Statistical Software 74, 1–26 (2016) for more detail.

Further information about the analyses / SPINE project is available by contacting the first or last authors (rachael.burke@lshtm.ac.uk or peter.macpherson@lstmed.ac.uk). Data requests for the real dataset can also be directed to MLW data department (data@mlw.mw) who may be able to facilitate data sharing, permission from QECH may be required.

Code and data on this repo is available for use under CC-BY license; please do acknowledge us as creator.

Note: The "docs" folder is there to create / hold the website content.  You are welcome to look at it (of course), but it's not the correct folder to find our data and code if you want to use it yourself.