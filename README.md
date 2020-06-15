# pyprobml
Python 3 code for the second edition of my book [Machine learning: a probabilistic perspective](http://people.cs.ubc.ca/~murphyk/MLbook/). This is work in progress, so expect rough edges.

## Notebooks

I have created [Jupyter notebooks](https://github.com/probml/pyprobml/tree/master/notebooks) for some of the chapters (more coming later). When you open a notebook, there will be a button at the top that says 'Open in colab'. If you click on this, it will start a virtual machine (VM) instance on Google Cloud Platform (GCP), running [Colab](https://colab.sandbox.google.com/notebooks/welcome.ipynb),  which has most of the libraries you will need (e.g., scikit-learn, tensorflow 2, JAX) pre-installed. Execute the code in the colab to temporally pip-install any remaining libraries. (You can select 'GPU' from the 'Runtime' menu at the top of Colab to make things run faster, but you will get logged out automatically if your session is idle for too long.) Alternatively, you can run these notebooks locally on your desktop in Jupyter, but then you will have to install the packages yourself (see instructions below).

<!--
* [Introduction](https://nbviewer.jupyter.org/github/probml/pyprobml/blob/master/notebooks/intro/intro.ipynb?flush_cache=true)
-->

## Scripts

Many of the figures in the book are generated by these  [scripts](scripts). To execute a script, cd (change directory) to the scripts folder, and then type 'python foo.py'. You can also run each script from inside a Python IDE (like Spyder).
Many of the scripts create plots, which are saved to ../figures.

To run the scripts, we assume you have installed numpy, scipy, matplotlib, seaborn, pandas, scikit-learn, etc.
(All of these are bundled with [anaconda](https://www.anaconda.com/distribution/).)
Some scripts rely on additional libraries, such as [Tensorflow 2.0](https://www.tensorflow.org/) and [JAX](https://github.com/google/jax). Scripts that need these libraries have filenames that end in tf and jax respectively.

## Table of contents

The book should become available (both in print, and online for free) in May 2021.
A snapshot (as of 3/11/20) of the book's table of contents is shown 
[here](https://github.com/probml/pyprobml/blob/master/toc1-200614.png)
and [here](https://github.com/probml/pyprobml/blob/master/toc2-200614.png).
Individual chapters will be made available
[here](https://github.com/probml/pyprobml/tree/master/chapters). 

 





