### Fundamentals of Music Processing 

> Based on the work done by the excellent folks at [FMP](https://www.audiolabs-erlangen.de/)

There are [binder](https://mybinder.org/) versions for each of the notebooks with my annotations as I go along learning audio processing and applying ML to it.

#### Basics

Python fundamentals including and up to [Python Style Guide](https://www.audiolabs-erlangen.de/resources/MIR/FMP/B/B_PythonStyleGuide.html) are not covered here.

[Multimedia](./basics/multimedia.ipynb) : 
Here is the associated *Binder* notebook for this
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/atg-abhishek/ml-for-audio/master?filepath=FMP%2Fnotebooks_binder%2Fbasics%2Fmultimedia.ipynb)


From a setup perspective, I am using the `conda` environment provided by the creators of these set of notebooks with the following additions:

* I also use [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) which can easily be installed using `pip install jupyterlab` and then run using `jupyter lab` instead of `jupyter notebook`
* I use `conda install --name FMP nb_conda_kernels` to have the specific kernels show up easily in the Jupyter notebooks. 