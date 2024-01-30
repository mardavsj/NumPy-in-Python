
![numpy_logo](https://www.davecwright.org/files/sps-files/figures/dave/numpy-logo.png)


NumPy stands for Numerical Python. It is a Python library used for working with arrays. It also has functions for working in domain of linear algebra and matrices.

NumPy was created by Travis Oliphant in 2005. It is an open source project and you can use it for free. 

[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white&color=darkblue)](https://github.com/numpy/numpy)


## Pre-requisites :
* Python
* Pip or Conda (depending on user)
## Installation :

Install NumPy with pip :

```bash
  pip install numpy
```

Install NumPy with conda :

```bash
  # Best practice, use an environment rather than install in the base env
  conda create -n my-env
  conda activate my-env
  # If you want to install from conda-forge
  conda config --env --add channels conda-forge
  # The actual install command
  conda install numpy
```


    
## NumPy Array 

NumPy array is a powerful N-dimensional array object and its use in linear algebra, fourier transform and random number capabilities. It provides an array object much faster than traditional Python lists.

#### Types of Array:
* One Dimensional Array
* Multi-Dimensional Array
## Why NumPy Array over Python List ?

* Using an array is faster than a list.
* A list cannot directly handle a mathematical operations, while array can.
* An array consumes less memory than a list.