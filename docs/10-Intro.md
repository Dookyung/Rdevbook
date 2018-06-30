

# (PART) Introduction {-} 

# Introduction

Data science is an exciting discipline that allows you to turn raw data into understanding, insight, and knowledge. The goal of "Data Scientist Handbook" is to help you learn the most important tools in R that will allow you to do data science. After reading this book, you'll have the tools to tackle a wide variety of data science challenges, using the best parts of R. 

한국은행에서의 경험을 바탕으로 경제학, 리서처의 관점에서 데이터 분석과 관련한 Best Practice를 제시

## What you will learn

Data science is a huge field, and there's no way you can master it by reading a single book. The goal of this book is to give you a solid foundation in the most important tools. Our model of the tools needed in a typical data science project looks something like this:

<img src="diagrams/data-science.png" width="75%" style="display: block; margin: auto;" />

프로그램언어를 배우는 것은 언어를 배우는 것과 같음
단어와 문법을 배워야하며 세련된 방식으로 대화하기 위해서는 Best Practice를 알아야 함
가장 좋은 방법은 Cheatsheet활용, 좋은 문법책을 선택, 그 나라에서 가서 살아보기(실제 개발자들이 프로그래밍한 프로그램을 가지고 놀기)

tidyverse


## RStudio Cheat Sheets

The cheat sheets make it easy to learn about and use some of our favorite packages. They are published in their respective PDF versions here: https://www.rstudio.com/resources/cheatsheets/, some are also available in the RStudio IDE under Help-Cheatsheets.

This repository contains the source Apple Keynote files or the current, archived and translated versions.

The cheat sheets use the creative commons copyright. Please see the LICENSE document for more details.







## Colophon

An online version of this book is available at <http://r4ds.had.co.nz>. It will continue to evolve in between reprints of the physical book. The source of the book is available at <https://github.com/hadley/r4ds>. The book is powered by <https://bookdown.org> which makes it easy to turn R markdown files into HTML, PDF, and EPUB.

This book was built with:


```r
devtools::session_info(c("tidyverse"))
#> Session info -------------------------------------------------------------
#>  setting  value                       
#>  version  R version 3.4.4 (2018-03-15)
#>  system   x86_64, darwin15.6.0        
#>  ui       X11                         
#>  language (EN)                        
#>  collate  en_US.UTF-8                 
#>  tz       Asia/Seoul                  
#>  date     2018-06-30
#> Packages -----------------------------------------------------------------
#>  package      * version    date       source                            
#>  assertthat     0.2.0      2017-04-11 cran (@0.2.0)                     
#>  backports      1.1.2      2017-12-13 cran (@1.1.2)                     
#>  base64enc      0.1-3      2015-07-28 cran (@0.1-3)                     
#>  BH             1.66.0-1   2018-02-13 CRAN (R 3.4.3)                    
#>  bindr          0.1        2016-11-13 CRAN (R 3.4.0)                    
#>  bindrcpp       0.2        2017-06-17 CRAN (R 3.4.0)                    
#>  broom          0.4.4      2018-03-29 cran (@0.4.4)                     
#>  callr          2.0.2.9001 2018-03-10 Github (r-lib/callr@3d39856)      
#>  cellranger     1.1.0      2016-07-27 CRAN (R 3.4.0)                    
#>  cli            1.0.0      2017-11-05 cran (@1.0.0)                     
#>  colorspace     1.3-2      2016-12-14 CRAN (R 3.4.0)                    
#>  compiler       3.4.4      2018-03-15 local                             
#>  crayon         1.3.4      2017-09-16 cran (@1.3.4)                     
#>  curl           3.1        2017-12-12 CRAN (R 3.4.3)                    
#>  DBI            0.8        2018-04-22 Github (jimhester/DBI@17f7e8f)    
#>  dbplyr         1.2.1      2018-02-19 CRAN (R 3.4.3)                    
#>  debugme        1.1.0      2017-10-22 cran (@1.1.0)                     
#>  dichromat      2.0-0      2013-01-24 CRAN (R 3.4.0)                    
#>  digest         0.6.15     2018-01-28 CRAN (R 3.4.3)                    
#>  dplyr          0.7.4      2017-09-28 CRAN (R 3.4.2)                    
#>  evaluate       0.10.1     2017-06-24 cran (@0.10.1)                    
#>  forcats        0.3.0      2018-02-19 CRAN (R 3.4.3)                    
#>  foreign        0.8-69     2017-06-22 CRAN (R 3.4.4)                    
#>  ggplot2        2.2.1.9000 2018-06-21 Github (tidyverse/ggplot2@1c09bae)
#>  glue           1.2.0.9000 2018-06-25 Github (tidyverse/glue@a2c0f8b)   
#>  graphics     * 3.4.4      2018-03-15 local                             
#>  grDevices    * 3.4.4      2018-03-15 local                             
#>  grid           3.4.4      2018-03-15 local                             
#>  gtable         0.2.0      2016-02-26 CRAN (R 3.4.0)                    
#>  haven          1.1.1      2018-01-18 CRAN (R 3.4.3)                    
#>  highr          0.6        2016-05-09 cran (@0.6)                       
#>  hms            0.4.2      2018-03-10 cran (@0.4.2)                     
#>  htmltools      0.3.6      2017-04-28 cran (@0.3.6)                     
#>  httr           1.3.1      2017-08-20 CRAN (R 3.4.1)                    
#>  jsonlite       1.5        2017-06-01 CRAN (R 3.4.0)                    
#>  knitr          1.20       2018-02-20 CRAN (R 3.4.3)                    
#>  labeling       0.3        2014-08-23 CRAN (R 3.4.0)                    
#>  lattice        0.20-35    2017-03-25 CRAN (R 3.4.4)                    
#>  lazyeval       0.2.1      2017-10-29 CRAN (R 3.4.2)                    
#>  lubridate      1.7.4      2018-04-11 cran (@1.7.4)                     
#>  magrittr       1.5        2014-11-22 cran (@1.5)                       
#>  markdown       0.8        2017-04-20 cran (@0.8)                       
#>  MASS           7.3-49     2018-02-23 CRAN (R 3.4.4)                    
#>  Matrix         1.2-12     2017-11-30 CRAN (R 3.4.4)                    
#>  methods        3.4.4      2018-03-15 local                             
#>  mgcv           1.8-23     2018-01-21 CRAN (R 3.4.4)                    
#>  mime           0.5        2016-07-07 CRAN (R 3.4.0)                    
#>  mnormt         1.5-5      2016-10-15 CRAN (R 3.4.0)                    
#>  modelr         0.1.1      2017-07-24 CRAN (R 3.4.1)                    
#>  munsell        0.4.3      2016-02-13 CRAN (R 3.4.0)                    
#>  nlme           3.1-131.1  2018-02-16 CRAN (R 3.4.4)                    
#>  openssl        1.0.1      2018-03-03 CRAN (R 3.4.3)                    
#>  parallel       3.4.4      2018-03-15 local                             
#>  pillar         1.2.1      2018-02-27 cran (@1.2.1)                     
#>  pkgconfig      2.0.1      2017-03-21 CRAN (R 3.4.0)                    
#>  plogr          0.2.0      2018-03-25 CRAN (R 3.4.4)                    
#>  plyr           1.8.4      2016-06-08 CRAN (R 3.4.0)                    
#>  praise         1.0.0      2015-08-11 cran (@1.0.0)                     
#>  psych          1.8.3.3    2018-03-30 cran (@1.8.3.3)                   
#>  purrr          0.2.5      2018-05-29 cran (@0.2.5)                     
#>  R6             2.2.2      2017-06-17 CRAN (R 3.4.0)                    
#>  RColorBrewer   1.1-2      2014-12-07 CRAN (R 3.4.0)                    
#>  Rcpp           0.12.17    2018-05-18 cran (@0.12.17)                   
#>  readr          1.1.1      2017-05-16 CRAN (R 3.4.0)                    
#>  readxl         1.0.0      2017-04-18 CRAN (R 3.4.0)                    
#>  rematch        1.0.1      2016-04-21 CRAN (R 3.4.0)                    
#>  reprex         0.1.2      2018-01-26 CRAN (R 3.4.3)                    
#>  reshape2       1.4.3      2017-12-11 CRAN (R 3.4.3)                    
#>  rlang          0.2.0.9001 2018-06-25 Github (tidyverse/rlang@ba4fb06)  
#>  rmarkdown      1.9        2018-03-01 cran (@1.9)                       
#>  rprojroot      1.3-2      2018-01-03 cran (@1.3-2)                     
#>  rstudioapi     0.7        2017-09-07 CRAN (R 3.4.1)                    
#>  rvest          0.3.2      2016-06-17 CRAN (R 3.4.0)                    
#>  scales         0.5.0.9000 2018-03-10 Github (hadley/scales@d767915)    
#>  selectr        0.3-2      2018-03-05 CRAN (R 3.4.4)                    
#>  stats        * 3.4.4      2018-03-15 local                             
#>  stringi        1.2.2      2018-05-02 cran (@1.2.2)                     
#>  stringr        1.3.1      2018-05-10 cran (@1.3.1)                     
#>  testthat       2.0.0      2017-12-13 cran (@2.0.0)                     
#>  tibble         1.4.2      2018-01-22 cran (@1.4.2)                     
#>  tidyr          0.8.0      2018-01-29 CRAN (R 3.4.3)                    
#>  tidyselect     0.2.4      2018-02-26 CRAN (R 3.4.3)                    
#>  tidyverse      1.2.1      2017-11-14 CRAN (R 3.4.2)                    
#>  tools          3.4.4      2018-03-15 local                             
#>  utf8           1.1.3      2018-01-03 cran (@1.1.3)                     
#>  utils        * 3.4.4      2018-03-15 local                             
#>  viridisLite    0.3.0      2018-02-01 CRAN (R 3.4.3)                    
#>  whisker        0.3-2      2013-04-28 CRAN (R 3.4.0)                    
#>  withr          2.1.2      2018-06-21 Github (r-lib/withr@dbcd7cd)      
#>  xml2           1.2.0      2018-01-24 CRAN (R 3.4.3)                    
#>  yaml           2.1.18     2018-03-08 cran (@2.1.18)
```


