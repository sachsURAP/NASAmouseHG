R Markdown
================

This is an R Markdown document. You can embed an R code chunk like this:

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

You can also embed plots:

![](plot_example_files/figure-markdown_github-ascii_identifiers/unnamed-chunk-2-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

To view the output of plots in your Rmarkdown file in GitHub, make sure `output` is set to `rmarkdown::github_document` above. This will create a Markdown (.md) version of your file with the plots embedded when you "Knit" the file in RStudio with `knitR`.
