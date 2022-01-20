# multivariate-adaptive-regression-splines
Installing the py-earth library for Python version > 3.6


Py-earth: an implementation of Jerome Friedman's multivariate adaptive regression splines. The py-earth package is only compatible with Python 3.6 or below at the time of writing.  using [~gohlke binaries](https://www.lfd.uci.edu/~gohlke/pythonlibs/) 


**(1) Make sure numpy >= 1.14.5**

```python
# load Libraries
import numpy

pip install numpy --upgrade
numpy.__version__
```
**Note: you may need to restart the kernel to use updated packages.**
keyboard shortcut: select the console (not the editor or the file explorer or some other part of the interface), then hit ```Ctrl``` + ```.```
 
**(2) Download whl version of windows binary for python extension packages** 

from this site: https://www.lfd.uci.edu/~gohlke/pythonlibs/. This page provides 32 and 64-bit Windows binaries of many scientific open-source extension packages for the official CPython distribution of the Python programming language. A few binaries are available for the PyPy distribution.

Search the page by ```Ctrl``` + ```F``` for ```sklearn_contrib_py_earth```.
Choose either 32-bit or 64-bit python for Python versions 3.7, 3.8 and 3.9.
Download the appropriate whl file to current working directory. A working directory is like a flag on your computer that tells Python where to start looking for your files related to a specific project. 


**Note: do not use the unofficial windows binaries in an application handling sensitive data.**
The files are unofficial (meaning: informal, unrecognized, personal, unsupported, no warranty, no liability, provided "as is") and made available for testing and evaluation purposes (https://www.reddit.com/r/Python/comments/6rdd21/psa_dont_use_the_unofficial_windows_binaries_in/).


**Note: make sure to download whl file to current working directory.** Getting the current working directory in python: 
 ```python
 # import the os module
import os

# get the current working directory
cwd = os.getcwd()

# print the current working directory
print("Current working directory: {0}".format(cwd))
```
 

**(3) Install the py-earth library – example for Python v3.8 64-bit**

```python
# install the py-earth library
pip install sklearn_contrib_py_earth-0.1.0-cp38-cp38-win_amd64.whl
```


**References**
1. https://machinelearningmastery.com/multivariate-adaptive-regression-splines-mars-in-python/
