Meu Primeiro Relatório
================

``` r
library(tidyverse)
```

Este é meu primeiro relatorio onde eu:

-   crio um plot
-   e me despido

``` r
mtcars %>% 
  ggplot(aes(mpg,cyl)) +
  geom_line(color="blue")
```

<img src="README_files/figure-markdown_github/unnamed-chunk-2-1.png" width="50%" style="display: block; margin: auto;" />

Ciao!
