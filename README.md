# acm-sage
Written by Jacob Hartzer and Christopher O'Neill.  

Provides a Python class `ArithmeticalCongruenceMonoid` for use with the computer algebra system [Sage](http://sagemath.org/) that adds functionality for working with [arithmetical congruence monoids](http://faculty.fairfield.edu/pbaginski/Papers/SubmittedACMSurvey%20RevisedReferee%2001.20.2013.pdf).  The package was developed as a semester project with [Jacob Hartzer](https://www.linkedin.com/in/jacobhartzer), an undergraduate student at Texas A&M University.  

Please note that this is an *alpha version* and subject to change without notice.  

## License
acm-sage is released under the terms of the [MIT license](https://tldrlegal.com/license/mit-license).  The MIT License is simple and easy to understand and it places almost no restrictions on what you can do with this software.

## Usage
To set up your machine to use acm-sage, do the following.  

* First, install Sage on your machine.  Instructions for doing so can be found [here](http://sagemath.org/).
* Next, download `ArithmeticalCongruenceMonoid.sage` and place it in your favorite folder.

The following code fragment gives an overview of how to use the `ArithmeticalCongruenceMonoid` class from within Sage, and more complete documentation will be added in the near future.

	load('/PATH_TO_FILE/ArithmeticalCongruenceMonoid.sage')
	hilbert = ArithmeticalCongruenceMonoid(1,4)
	print hilbert.Factorizations(441)
	print hilbert.DeltaSet(441)
