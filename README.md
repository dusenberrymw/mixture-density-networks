# Mixture Density Networks

An exploration of mixture density networks.

## Background
A _mixture density network_ (MDN) is an interesting model formalism built within the general framework of neural networks and probability theory for working on supervised learning problems in which the target variable cannot be easily approximated by a single standard probability distribution.  Essentially, an MDN allows one to model a conditional probability distribution p(y|x) as a mixture of distributions, in which the individual distributions and the corresponding mixture coefficients are parameterized by functions of the inputs x.

## Notebook
- [`mixture_density_networks.ipynb`](mixture_density_networks.ipynb)

## Blog post
- [mikedusenberry.com/mixture-density-networks](http://mikedusenberry.com/mixture-density-networks)

## Resources
1. [Pattern Recognition and Machine Learning (PRML)](https://www.microsoft.com/en-us/research/people/cmbishop/#!prml-book), pp. 272-277, pp. 430-435
2. [@hardmaru's](https://twitter.com/hardmaru) MDN blogs: [http://blog.otoro.net/2015/06/14/mixture-density-networks](http://blog.otoro.net/2015/06/14/mixture-density-networks), [http://blog.otoro.net/2015/11/24/mixture-density-networks-with-tensorflow](http://blog.otoro.net/2015/11/24/mixture-density-networks-with-tensorflow)
3. [http://edwardlib.org/tutorials/mixture-density-network](http://edwardlib.org/tutorials/mixture-density-network)
