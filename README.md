*“Computing with semigroups in GAP”* by Wilf Wilson<br />
*“GAP in Algebraic Research” summer school*<br />
19<sup>th</sup> to 22<sup>nd</sup> November 2018<br />
[https://github.com/wilfwilson/semigroups-in-algebraic-research](https://github.com/wilfwilson/semigroups-in-algebraic-research)<br />
[![(Link to launch Binder)](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/wilfwilson/semigroups-in-algebraic-research/master)

# Computing with semigroups in GAP

A semigroup is a set with an associative binary operation. Every group is a
semigroup, but there are many other kinds of semigroups that are not groups.

In this course I will:
* introduce you to some introductory information about semigroups,
* explain the main ideas behind computation with semigroups,
* describe some of the packages and functionality in GAP for semigroups,
  and
* set some exercises for you to explore these topics in GAP.


## Jupyter notebooks

#### Pre-rendered versions on GitHub

The material for this mini-course is presented via several **Jupyter
notebooks**. This is made possible by the [JupyterKernel
package](https://gap-packages.github.io/JupyterKernel) for GAP, created by
[Markus Pfeiffer](https://markusp.morphism.de), which provides the interface
between a Jupyter notebook and GAP.

GitHub provides the ability to view pre-rendered Jupyter notebooks in the
browser. All of the Jupyter notebooks in this mini-course are contained in this
GitHub repository. By clicking the relevant link, you can view a
pre-rendered version of the corresponding notebook, right here on GitHub:

* [An introduction to computational semigroup theory](notebooks/intro.ipynb)
* [The NumericalSgps package for GAP](notebooks/numericalsgps.ipynb)
* [The Smallsemi package for GAP](notebooks/smallsemi.ipynb)
* [The Semigroups package for GAP](notebooks/semigroups.ipynb)

The relevant exercises are contained at the bottom of each Jupyter notebook.


#### Interactive versions on Binder

It is also possible to run an interactive version of each of these Jupyter
notebook in the browser, by using **Binder**. This will let you edit, execute,
and extend the code in each notebook..

This is particularly useful if you are using GAP in Windows, since in this case,
unfortunately you will not be able to use the newest version of the Semigroups
package for GAP, which contains many new features. However, the downsides of
this are that Binder is *much slower* than your own computer, and this option
requires that you become familiar with Jupyter notebooks.

You can load Binder by clicking the [![(Link to launch Binder)](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/wilfwilson/semigroups-in-algebraic-research/master) badge at the top of any notebook, or by
clicking the following link:

* [https://mybinder.org/v2/gh/wilfwilson/semigroups-in-algebraic-research/master](https://mybinder.org/v2/gh/wilfwilson/semigroups-in-algebraic-research/master)


## Addendum

* [Some advertising](notebooks/advertising.ipynb)
