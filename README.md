# ugtm: Generative Topographic Mapping with Python.

Link to the package documentation: http://ugtm.readthedocs.io/en/latest/

GTM (Generative Topographic Mapping) is a dimensionality reduction algorithm (as t-SNE, LLE, etc) created by Bishop et al. (https://www.microsoft.com/en-us/research/wp-content/uploads/1998/01/bishop-gtm-ncomp-98.pdf) and a probabilistic counterpart of Kohonen maps.

ugtm is a python package implementing GTM and GTM prediction algorithms. ugtm contains the core functions and runGTM.py (in bin directory) is an easy-to-use program. The kernel version of the algorithm (kGTM) is also implemented. You can also generate regression or classification maps, or evaluate the predictive accuracy (classification) or RMSE/R2 (regression) in repeated cross-validation experiments.

## Install ugtm

Simple installation:
- pip install ugtm

If you get error messages, try upgrading packages:
- pip install --upgrade pip numpy scikit-learn matplotlib scipy mpld3 jinja2
- sudo pip install --upgrade pip numpy scikit-learn matplotlib scipy mpld3 jinja2

If you have problems with anaconda packages, try to create a virtual env called "p2" for python 2.7.14:
- conda create -n p2 python=2.7.14 numpy=1.14.5 scikit-learn=0.20 matplotlib=2.2.2 scipy=0.19.1 mpld3=0.3 jinja2=2.10
- source activate p2
- pip install ugtm

Or p3 for python 3.6.6:
- conda create -n p3 python=3.6.6 numpy=1.14.5 scikit-learn=0.20 matplotlib=2.2.2 scipy=0.19.1 mpld3=0.3 jinja2=2.10
- source activate p3
- pip install ugtm


## Documentation

[Readthedocs](https://ugtm.readthedocs.io/)


## Prerequisites

Python 2.7 or + (tested on Python 3.4.6 and Python 2.7.14)

and following packages:
- scikit-learn>=0.20
- numpy>=1.14.5
- matplotlib>=2.2.2
- scipy>=0.19.1
- mpld3>=0.3
- jinja2>=2.10

## Citing ugtm

Cite ugtm version and the [following paper](https://openresearchsoftware.metajnl.com/articles/10.5334/jors.235/):

```
@ARTICLE{Gaspar2018-qt,
  title   = "ugtm: A Python Package for Data Modeling and Visualization Using
             Generative Topographic Mapping",
  author  = "Gaspar, H{\'e}l{\'e}na Alexandra",
  journal = "Journal of Open Research Software",
  volume  =  6,
  pages   = "215",
  month   =  dec,
  year    =  2018
}
```

## Principal author / admin

Héléna A. Gaspar, hagax8@gmail.com, https://github.com/hagax8


