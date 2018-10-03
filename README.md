pxweb
====== 

[![Build Status](https://travis-ci.org/rOpenGov/pxweb.svg?branch=master)](https://travis-ci.org/rOpenGov/pxweb)
[![Stories in Ready](https://badge.waffle.io/ropengov/pxweb.png?label=TODO)](http://waffle.io/ropengov/pxweb)
[![Coverage Status](https://coveralls.io/repos/rOpenGov/pxweb/badge.svg)](https://coveralls.io/r/rOpenGov/pxweb) [![rstudio mirror downloads](http://cranlogs.r-pkg.org/badges/grand-total/pxweb)](https://github.com/metacran/cranlogs.app)
[![cran version](http://www.r-pkg.org/badges/version/pxweb)](http://cran.rstudio.com/web/packages/pxweb)

NOTE: The pxweb R package has been temporarily removed from CRAN. We are working on the issue (as of 5/2018), and wish to have it back in CRAN soon. Meanwhile, you can install the Github development version as follows:



```r
library(devtools)
install_github('ropengov/pxweb')
```

In some cases, the organization requires manual proxy settings. This can be set as follows:


```r
library(devtools)
library(httr)
set_config(
  use_proxy(url="organizationProxyURL", port=1234)
)
install_github('ropengov/pxweb')
```
 


# Overview of pxweb R package

pxweb is an R package to interface with the PX-WEB API, and it offers
methods to utilize information about the data hierarchy stored behind
the PX-WEB API used by Statistics authorities in Finland, Sweden and
many other countries. Many API services are still in their early
stages, and data quality is sometimes compromised. Issue reports are
welcome.

For installation and usage, check the [tutorial page](https://github.com/rOpenGov/pxweb/blob/master/vignettes/pxweb.md).  

Authors: [Måns Magnusson](https://github.com/MansMeg/), [Love Hansson](https://github.com/LCHansson/), [Leo Lahti](https://github.com/antagomir). Part of [rOpenGov](http://ropengov.github.io/).
  
You are welcome to contact us:

  * [submit suggestions and bug reports](https://github.com/ropengov/pxweb/issues) (provide the output of `sessionInfo()` and `packageVersion("pxweb")`)
  * [send a pull request](https://github.com/ropengov/pxweb/)
  * public email list ropengov-forum@googlegroups.com
  * join IRC at ropengov@Freenode
  * [join or follow our community](http://ropengov.github.io/contribute/)  




