# Using latex with Binder

[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/binder-examples/latex/master)

This repository demonstrates how to install latex alongside matplotlib
for Binder. This requires a few different build components:

* `apt.txt` for apt-installing the latex components
* `requirements.txt` for installing the python dependencies
* `postBuild` for forcing matplotlib to build the font cache

Thanks to [m-weigand](https://github.com/m-weigand) for giving
[inspiration for this repo](https://github.com/m-weigand/binder-example-latex-mpl/blob/master/index.ipynb)!
