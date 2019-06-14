# MTL-Lab-Season-Report-Template

## Installation

Before you download .zip or git clone this repos, you do these below in your `RStudio`.

```
# Install from CRAN
install.packages('rmarkdown')

# Or if you want to test the development version,
# install from GitHub
if (!requireNamespace("devtools"))
  install.packages('devtools')
devtools::install_github('rstudio/rmarkdown')
```

```
install.packages("tinytex")
tinytex::install_tinytex()  # install TinyTeX
```

Reference: https://bookdown.org/yihui/rmarkdown/installation.html



## Getting Start

1. You can download the whole repos on the right upper button or use `git clone` command.
2. First, change the yaml information in `Season_Report_Template.Rmd` to yours.
3. Then, try to click the `knit` button in `RStudio`.
4. Check if there is any error. if not, you can start $\LaTeX$ing in RStudio (and plotting data with R)!