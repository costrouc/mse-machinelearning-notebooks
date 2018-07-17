[![Binder](https://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/costrouc/mse-machinelearning-notebooks/master?urlpath=lab/tree/notebooks/Overview.ipynb)

[![pipeline status](https://gitlab.com/costrouc/mse-machinelearning-notebooks/badges/master/pipeline.svg)](https://gitlab.com/costrouc/mse-machinelearning-notebooks/commits/master)

# Machine Learning with a focus on Material Science

A presentation given and written by Christopher Ostrouchov all
contributions are welcome. We will be using the materials project and
it's available data to "predict" material properties through machine
learning. Many of the examples may be trivial but the focus is on
introducing the workflow that is typical in machine learning.

# Introduction to Python and Packages

The goal of this set of notebooks is to introduce you to the most
important concepts of machine learning. While there are many many
algorithms for fitting your data the methodology of gathering,
sanitizing, investigating, and evaluating the goodness of fit is
mostly the same. I hope to show you the process along with showing
some methods from each branch of machine learning. Python has evolved
into a great solution for easily performning these steps and along
with R are great choices. My favorite description of Python is that it
is the 2nd best language for every problem. Also it is probably the
best glue language out there.

Python is a language that while it comes with "batteries included"
most of the functionality is provided through packages. I myself may
consider myself an "expert" the standard library (packages that are
included by default with python) but there are always new packages to
learn. The packages that we will be using:

 - [jupyter notebooks](https://jupyter.org/) for [literate
   programming](https://en.wikipedia.org/wiki/Literate_programming)

 - [requests](http://docs.python-requests.org/en/master/) for
   gathering the materials project data

 - [pandas](https://pandas.pydata.org/) for storing data, sanitizing,
   and investigating the data. A supercharged excell spreadsheet.

 - [matplotlib](https://matplotlib.org/users/pyplot_tutorial.html)
   visualizing data

 - [numpy](http://www.numpy.org/) used underneath the covers for
   pandas and basis of linear algebra in python

 - [scikit-learn](http://scikit-learn.org/) most popular machine
   learning library. Does not perform neural network
   calculations. Overview of available algorithms (does not cover all)
   [link](http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html)
   
 - [pymatgen](https://github.com/materialsproject/pymatgen/) a package
   by the Materials Project for working with material science
   structures and analysis of calculations.

These packages have many many features but learning these core
libraries will be more than enough for getting started.

Resources that we will be using that are not python specific are:

 - [mybinder](https://mybinder.org/) which is a way to make a custom
   programming environment available for free hosted on google
   cloud. Note that resources are limited about 1 CPU and 8 GiB RAM
   per instance. It is awesome you should use it too.

 - [materialsproject](https://materialsproject.org/) based at Lawrence
   Berkely National Lab using the NERSC resources they provide data
   from their VASP similations available using a [RESTfull
   API](https://www.quora.com/What-is-a-REST-API).

# Getting Started

To get started we will lanch the introduction notebook with binderhub.

[![Binder](https://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/costrouc/mse-machinelearning-notebooks/master?urlpath=lab/tree/notebooks/Overview.ipynb)

# Contributing

All contributions, bug reports, bug fixes, documentation improvements,
enhancements and ideas are welcome! These should be submitted at the
[Gitlab repository](https://gitlab.com/costrouc/
mse-machinelearning-notebooks). Github is only used for visibility.

Contributors:
 - [Chris Ostrouchov](https://gitlab.com/costrouc) (maintainer)

# License

MIT
