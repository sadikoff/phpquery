# Revisiting PhpQuery

[![Build Status](https://travis-ci.org/wittiws/phonarc.png?branch=master)](https://travis-ci.org/wittiws/phonarc)

## Basic usage of this fork

```` php
// This gives you the phpQuery object as normally used.
use PhpQuery\PhpQuery as phpQuery;

// This creates the pq() function in your namespace.
PhpQuery::use_function(__NAMESPACE__);

// This creates the pq() function in the global namespace.
PhpQuery::use_function();
````

## About this fork

This fork includes several modernizations:

1. Merged https://github.com/kevee/phpquery/tree/phpquery-css with https://github.com/electrolinux/phpquery
2. Removed CSSParser from this repository and included it via composer
3. Added PhpQuery\ namespace
4. Adjusted the folder structure to reflect usage of PSR-4
5. Corrected the unit tests and integrated with travis-ci

Beyond these adjustments, this project will be minimally maintained. For more phpQuery usage information and fork history, I highly recommend you review the https://github.com/electrolinux/phpquery README.
