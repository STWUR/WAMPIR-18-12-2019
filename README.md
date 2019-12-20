# WAMPIR meeting on 18-12-2019

- [Wei Jiang's presentation on missing data analysis:](https://github.com/STWUR/WAMPIR-18-12-2019/blob/master/misstuto_tourR.pdf)

Imagine you are solving a linear regression but there are a lot of missing values in your design matrix, how can you deal with so many "NA"? The trouble may be caused by survey non-responses, lost records or machine failures.
Classical packages performing estimation would let you ignore all the lines with missingness, as a result, much information would be lost. A more reasonable method to handle this problem, is modifying an estimation process so that the method can be applied to incomplete data. For example, one can use the Expectation-Maximization (EM) algorithm to obtain the maximum likelihood estimate despite missing values.
Another popular choice is imputation, followed by classical regression procedure on imputed dataset. In this presentation, I will talk about different types of missing data, review several imputation methods and demonstrate how to estimate parameters based on EM algorithm with R.

[Wei Jiang](https://sites.google.com/site/weijiangstat/home)
