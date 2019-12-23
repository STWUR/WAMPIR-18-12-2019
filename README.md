# WAMPIR meeting on 18-12-2019

- [Wei Jiang's presentation on missing data analysis:](https://github.com/STWUR/WAMPIR-18-12-2019/blob/master/misstuto_tourR.pdf)

  Imagine you are solving a linear regression but there are a lot of missing values in your design matrix, how can you deal with so many "NA"? The trouble may be caused by survey non-responses, lost records or machine failures.
  Classical packages performing estimation would let you ignore all the lines with missingness, as a result, much information   would be lost. A more reasonable method to handle this problem, is modifying an estimation process so that the method can be applied to incomplete data. For example, one can use the Expectation-Maximization (EM) algorithm to obtain the maximum likelihood estimate despite missing values.
  Another popular choice is imputation, followed by classical regression procedure on imputed dataset. In this presentation, I will talk about different types of missing data, review several imputation methods and demonstrate how to estimate parameters based on EM algorithm with R.

  [Wei Jiang](https://sites.google.com/site/weijiangstat/home)




Stochastic Variational Inference, Michal Kurtys

Suggested readings:

Books:
* Doing Bayesian Data Analysis, Second Edition: A Tutorial with R, JAGS, and Stan, John Kruschke  https://www.amazon.com/Doing-Bayesian-Data-Analysis-Tutorial/dp/0124058884
* Bayesian Analysis with Python: Introduction to statistical modeling and probabilistic programming using PyMC3 and ArviZ, 2nd Edition, Osvaldo Martin. https://www.amazon.com/gp/product/1789341655/ref=dbs_a_def_rwt_bibl_vppi_i0
* Pattern Recognition andMachine Learning, Christopher M. Bishop http://users.isr.ist.utl.pt/~wurmd/Livros/school/Bishop%20-%20Pattern%20Recognition%20And%20Machine%20Learning%20-%20Springer%20%202006.pdf


Tutorials:
* https://twiecki.io/blog/2015/11/10/mcmc-sampling/
* https://pyro.ai/examples/intro_part_i.html
* https://www.shakirm.com/papers/VITutorial.pdf


Papers:
Stochastic Variational Inference, http://www.columbia.edu/~jwp2128/Papers/HoffmanBleiWangPaisley2013.pdf
