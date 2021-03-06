R Markdown Test
================
Linh Bun
September 3, 2017

R Markdown
----------

### Alternative Output

RStudio can also generate `Markdown` document (as intermediate steps). `R Markdown` `==>` `Markdown` `==>` `HTML` document. In this case, we could add the following `R` code:

``` r
output: 
  html_document:
    keep_md: true
```

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist    
    ##  Min.   : 4.0   Min.   :  2  
    ##  1st Qu.:12.0   1st Qu.: 26  
    ##  Median :15.0   Median : 36  
    ##  Mean   :15.4   Mean   : 43  
    ##  3rd Qu.:19.0   3rd Qu.: 56  
    ##  Max.   :25.0   Max.   :120

Including Plots
---------------

You can also embed plots, for example:

![](rmarkdown_test_files/figure-markdown_github-ascii_identifiers/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
