

[Lecture 2 - Bayesian inference](https://www.youtube.com/watch?v=guTdrfycW2Q)  

## Intro

* The two contexts of statistical modeling:
  * the model itself (the _small world_), where all possibilities are known and there are no (pure) surprises.
  * the context where the model is deployed (the _large world_), which contains observations not known/imagined in the small world.

* A central challenge of statistical modeling is distinquishing and navigating the two contexts (made specially difficult considering all models are essentially incomplete representations of the large world).


## Garden of forking data

Bayesian analysis - at its core - works by counting all possibilities to make inferences about specific scenarios (the name is a reference to Borges's essay about a book where, starting from a common point, every possible sequence takes place simultaneously).

Counting all possibilities lets us rank our hypothesis _quantitatively_, based on both the assumptions and the data available to us. In the _small world_, this can guarantee the best possible inference based on the available information.

**Rules for bayesian updating**

1. State a causal model that explains the observations (given each possible explanation)
2. For each explanation, count the number of ways the data could arise
3. Estimate relative possibility from (2), as a relative value

**Characteristics of bayesian analysis**

- There is no _minimum_ sample size.
- The shape of _the curve_ embodies the sample size.
- The estimate is the curve; point estimates don't play a big role. All calculations and estimation using the bayesian model must always use the entire distribution.
- There is no one _true_ interval


## Resources

* Chapter 2 - Small worlds and large worlds 
* The Garden of Forking Paths, by Jorge Luis Borges
