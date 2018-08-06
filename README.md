# Using latex with Binder

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/v2/gh/binder-examples/latex/master?filepath=index.ipynb)

This repository demonstrates how to install latex alongside matplotlib
for Binder. This repository also makes use of [JupyterLab Latex](https://github.com/jupyterlab/jupyterlab-latex) to render latex files in Jupyter lab. This requires a few different build components:

* `apt.txt` for apt-installing the latex components
* `environment.yml` for installing the python dependencies
* `postBuild` for forcing matplotlib to build the font cache and for installing JupyterLab Latex.

Thanks to [m-weigand](https://github.com/m-weigand) for giving
[inspiration for this repo](https://github.com/m-weigand/binder-example-latex-mpl/blob/master/index.ipynb)!
