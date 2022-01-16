
**Link to lecture**: https://www.youtube.com/watch?v=cclUd_HoRlo



## Golems

Scientific models are like [golems](https://en.wikipedia.org/wiki/Golem); constructs engineered for specific purposes. These are neither true nor false, and can be unyielding in their logic. Golems themselves aren't wise; they are each useful in particular contexts (which is why there are so many diverse golems). A decision tree is an example of a golem. 

It is possible to learn and practice statistical science by learning a lot of different golems. This isn't good enough for research (specially research that pushes boundaries), because it is impossible to know what is and isn't appropriate beforehand. A golem cannot always discern when a context is inappropriate for its answers. This means a golem can fail in unpredictable ways when applied to a context it wasn't engineered for.

What is needed is a unified theory of golem engineering: a set of foundational principles for designing, building, and refining context-specific statistical models or procedures. The goal of this course, then, is to learn how to re-think statistical inference as a set of such strategies, instead of a bunch of predefined golems.


## On falsifying hypotheses

The goal of statistical inference is not to _test_ the [null hypothesis](https://en.wikipedia.org/wiki/Null_hypothesis)  (or alternately - to falsify the research hypothesis). Deductive falsification is nearly impossible because:

* A hypothesis, by itself, isn't useful unless it is supported by a set of cause-effect relationships that are also validated by some data. *Process models* formally describe causal structures, and *statistical models* describe the associations between causes and their effects.  This makes it hard to falsify unique null hypothesis:
	* a statistical model can correspond to more than one process model.
	* a hypothesis can correspond to more than one process model.
	* a statistical model can correspond to more than one hypothesis.

* Data, how it is collected, and how it is processed - are subject to:
	* observation errors; represented by false positives and false negatives
	* continuous hypotheses; most real-world hypotheses aren't black-or-white. Instead, they make claims about the distribution of data (or the frequency of observations)

* Falsification is a consensus-driven activity. Scientific communities come to _regard_ certain hypotheses as false (such as the geocentric model of the universe) but this is done by consensus, and not always because of evidence. 


## What now?

Given a hypothesis, we know we can't really falsify it...so where do we go from here? One thing we _can_ focus on, is on the models that support (or not) the hypothesis. Why study models? Because we cant reliably predict the result of an intervention unless we understand _why_ something happens in the first place, and models are our way of answering the _why_. 

We use models, then, to do mainly 3 things for us:

* To help assess the hypothesis (to design our inquiries so that the models can learn from the data)
* To make sense of the data (to extract information)
* To make predictions

This course focuses on a few tools to help do the 3 things:

* **Bayesian data analysis**: essentially, counting the numbers of ways the data could happen according to our assumptions. This takes questions in the form of models, and answers them with probability distributions. Bayesian golems treat randomness as a property of information, not of the world (therefore, if we had enough information, we could predict anything). 

* **Model comparison**: choosing between many plausible models (using _cross-validation_ and _information criteria_), specially when complex models are easily subject to problems of _overfitting_.
	
* **Multilevel models**:  models that contain other models (models have _parameters_ that can stand-in for other models); to address issues like overfitting, clustered observations, etc.

* **Graphical causal models**: models for causal prediction (such as _Directed Acyclic Graphs_), which are useful when we use models to intervene in the world - because most everything can be represented by causal networks.




