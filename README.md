# twr

Slides for the [Toronto Workshop on
Reproducibility](https://canssiontario.utoronto.ca/event/toronto-workshop-on-reproducibility-2023/)
(TWR) 2023

## To reproduce this slides

Open (or direct) R to the root of this directory. Once R is opened, it
will recognize **renv** and install it. Then, run

```r
renv::restore()
```

to install all the required packages.

Restart R and run

```r
rmarkdown::render("slides-twr-gesla.Rmd")
```
