# db.rstudio.com

This repo (and resulting website) is licensed as [CC BY-SA](LICENSE.md).

```r
library(convertsite)

ov <- list()
ov$project$`output-dir` <- "docs"

convert_to_quarto(setup_override = ov)

quarto::quarto_serve()
```