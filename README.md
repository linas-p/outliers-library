[![Build Status](https://travis-ci.org/linas-p/outliers-library.svg?branch=master)](https://travis-ci.org/linas-p/outliers-library) [![Coverage Status](https://coveralls.io/repos/linas-p/outliers-library/badge.svg?branch=master&service=github)](https://coveralls.io/github/linas-p/outliers-library?branch=master)

# ouliers-library
Library for unknown number of outliers detection. [In progress!]

Outlier detection when outlier number are unknown were my master thesis topic. So I finaly prepared implement it in lower level so this imlementation(in c++) will be more flexibal and faster R. 

There is two reasons for this library to exist: 
1) lower level implementation allow generate larger samples w/o keeping in memory N*M (i.e assume we want sample size N=1000, and generations M=10000000 ).
2) Its will we easy extend library to any other statistics generations.
