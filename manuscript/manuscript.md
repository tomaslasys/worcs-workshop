Untitled
================
20 October, 2022

This manuscript uses the Workflow for Open Reproducible Code in Science
\[@vanlissaWORCSWorkflowOpen2020\] to ensure reproducibility and
transparency. All code <!--and data--> are available at
<git@github.com:tomaslasys/worcs-workshop.git>.

This is an example of a non-essential citation (@
**vanlissaWORCSWorkflowOpen2020?**). If you change the rendering
function to `worcs::cite_essential`, it will be removed.
\[@goedecke_measuring_2018\], (@ Goedecke et al. 2018), \[@goedecke\]

<!--The function below inserts a notification if the manuscript is knit using synthetic data. Make sure to insert it after load_data().-->

## GitHub Documents

This is an R Markdown format used for publishing markdown documents to
GitHub. When you click the **Knit** button all R code chunks are run and
a markdown file (.md) suitable for publishing to GitHub is generated.

## Including Code

You can include R code in the document as follows:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](manuscript_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-goedecke_measuring_2018" class="csl-entry">

Goedecke, Thomas, Daniel R. Morales, Alexandra Pacurariu, and Xavier
Kurz. 2018. “Measuring the Impact of Medicines Regulatory Interventions
– Systematic Review and Methodological Considerations.” *British Journal
of Clinical Pharmacology* 84 (3): 419–33.
<https://doi.org/10.1111/bcp.13469>.

</div>

</div>
