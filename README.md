# Benchmark
Benchmark Studies For Identifying Optimal Methods for Package Development

While developing functions and packages, I occasionally face decisions about how to go about implementation of various methods.  Most commonly, the choice is with respect to whether or not I should import a function from another package.  Benchmarking forms a major part of my decision, as I have a preference for using the fastest methods available. However, ease of use and protection against errors are other aspects that must be considered.  

The analyses in this repository benchmark the different methods to assist and document the decision making process.

## Expectation of Analysis

Each analysis will provide 

* minimal working examples of the functions/expressions to be benchmarked.
* benchmarks for the functions/expressions under an assortment of sample sizes
    + Note that some methods scale better than others.
* Discussion regarding the decision of which method to implement. This may include discussion about ease of use and protection against errors.
* Each analysis will be rendered to a markdown document (`.md` file) so that the images may be viewed in the GitHub UI.
