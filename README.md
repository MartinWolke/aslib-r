coseal-algsel-benchmark-repo
============================

* Offical CRAN release site:
  http://cran.r-project.org/web/packages/algselbench/index.html

* R Documentation in HTML:
  http://www.rdocumentation.org/packages/algselbench

* Run this in R to install the current GitHub version:
  ```splus
  devtools::install_github("berndbischl/coseal-algsel-benchmark-repo/algselbench")
  ```

* [Further installation instructions](https://github.com/tudo-r/PackagesInfo/wiki/Installation-Information)

* Travis CI: [![Build Status](https://travis-ci.org/berndbischl/algselbench.png)](https://travis-ci.org/berndbischl/alg)


## Validating the structure of a benchmark data set

You need:

* python2.7
* package: liac-arff (https://pypi.python.org/pypi/liac-arff/1.1), 
  e.g., call: $ pip install -U liac-arff

To run the validator:

`python trunk/data_check_tool_python/src/main.py --dir trunk/data/maxsat12-pms/`


## Available algorithm selection scenarios

http://berndbischl.github.io/coseal-algsel-benchmark-repo/scenario-pages/index.html

