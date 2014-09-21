# Bayes

Helping humans cope with uncertainty since 1763.

This is an in-progress attempt to express some simple probability theory in literate python, to illustrate the way Bayesian inference works in the context of data analysis. Started at the very end of [Astro Hack Week 2014](http://astrohackweek.github.io/).

### Key concepts:

* The rigorous tracking of assumptions
* The universality of uncertainty, and the symmetry between "data" `d` and "parameters" `theta` in `Pr(theta|d)` and related distributions.
* The usefulness, and importance, of *samples* drawn from PDFs
* Putting the emphasis on *belief* rather than *truth*

### Notebooks:

* [Introduction](http://nbviewer.ipython.org/github/drphilmarshall/bayes/blob/master/Introduction.ipynb)

### Challenges:

* Making objects that obey the rules of probability theory, while remaining functional in terms of being able to generate samples, represent themselves as latex strings etc.
* Keeping notebooks compact and readable, and always viewable in their entirety via nbviewer

### Authors:

* Phil Marshall (KIPAC, Stanford University)
* Jonathan Sick (Queens University, Kingston)

We are open to collaboration via issues and pull requests! Fork away, keep in touch.
