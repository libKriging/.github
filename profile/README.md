## libKriging

This organization is dedicated to libKriging project: a C++ library for Kriging/Gaussian process regression.

Main features of libKriging are:

* Standard implementation of most common kriging: 
  * ordinary/universal kriging 
  * __nugget__ (homoskedastic) or __noise__ (heteroskedastic)
  * __optimization__ of hyper-parameters (range, nugget, variance, ...) based on log-likelihood, leave-one-out, log-marginal-posterior
  * (pre-)__normalization__ of conditional data
* Comparison/testing against some standarad kriging libraries:
  * https://CRAN.R-project.org/package=DiceKriging
  * https://CRAN.R-project.org/package=RobustGaSP
* Compatibility with commons __OS__:
  * __Windows__
  * __Linux__
  * __OSX__ (intel & ARM)
* (Almost) full wrapper availables for:
  * __Python__: https://pypi.org/project/pylibkriging/
  * __R__: https://github.com/libKriging/rlibkriging
  * __Octave__
  * __Matlab__
* __Documentation__: https://libKriging.readthedocs.io
  
Entry points:

* for users: https://libKriging.readthedocs.io
* for developpers: https://github.com/libKriging/libkriging
