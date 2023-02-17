## Bayesian logistic regression with Mici and PyStan

Notebooks illustrating estimating the posterior in a Bayesian logistic regression problem using the Markov chain Monte Carlo methods implemented in [Mici](https://github.com/matt-graham/mici) and [PyStan](https://pystan.readthedocs.io/en/latest/). [ArviZ](https://python.arviz.org/en/stable/) is used to compute chain summary statistics and [Corner](https://corner.readthedocs.io/en/latest/) to plot pairwise posterior marginals.

The notebooks should be runnable from a Python 3.8+ environment with the packages listed in the [`requirements.txt`](requirements.txt) file installed.

To install the requirements in the current environment using `pip` run

```
pip install -r requirements.txt
```

from the root directory of a clone of the repository.

A Jupyter Lab instance can then be launched to allow viewing and running the notebooks locally by running

```
jupyter lab
```