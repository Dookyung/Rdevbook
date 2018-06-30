
# ETC

## 1.3.4 Hypothesis confirmation

It’s possible to divide data analysis into two camps: hypothesis generation and hypothesis confirmation (sometimes called confirmatory analysis). The focus of this book is unabashedly on hypothesis generation, or data exploration. 


## tidyverse conflict message

> Take careful note of the conflicts message that's printed when you load the tidyverse. It tells you that dplyr overwrites some functions in base R. If you want to use the base version of these functions after loading dplyr, you'll need to use their full names: `stats::filter()` and `stats::lag()`.

`tidyverse` 패키지는 로드할 때 "conflict" 메시지가 나타나는데 이는 dplyr가 base R의 함수를 overwrite했다는 의미 
