### Fundamentals of Music Processing 

> Based on the work done by the excellent folks at [FMP](https://www.audiolabs-erlangen.de/)

There are [binder](https://mybinder.org/) versions for each of the notebooks with my annotations as I go along learning audio processing and applying ML to it.

#### Setup

For the data files that are used, please get them from the [zip file here](https://www.audiolabs-erlangen.de/resources/MIR/FMP/FMP_1.0.1.zip) and place them at the same level as the `notebooks_binder` folder in this repo to get the examples to work exactly as is. If you are using the Binder environment, you can change the `data` related filepaths to point to a remote storage solution like [Blob storage](https://azure.microsoft.com/en-in/services/storage/blobs/). *Helpful instructions for that are present on the link there, Azure offers some free storage credits that you can use.*

The filepaths for data and other references is assuming that `jupyter lab` has been launched in the `FMP` directory.

From a setup perspective, I am using the `conda` environment provided by the creators of these set of notebooks with the following additions:

* I also use [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) which can easily be installed using `pip install jupyterlab` and then run using `jupyter lab` instead of `jupyter notebook`
* I use `conda install --name FMP nb_conda_kernels` to have the specific kernels show up easily in the Jupyter notebooks. 

#### Basics

Python fundamentals including and up to [Python Style Guide](https://www.audiolabs-erlangen.de/resources/MIR/FMP/B/B_PythonStyleGuide.html) are not covered here.

[Multimedia](./basics/multimedia.ipynb) : 
Here is the associated *Binder* notebook for this
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/atg-abhishek/ml-for-audio/master?filepath=FMP%2Fnotebooks_binder%2Fbasics%2Fmultimedia.ipynb)

