This project helps train a classifier to be able to detect [PE files](https://en.wikipedia.org/wiki/Portable_Executable) as either malicious or legitimate. It tries out 6 different classification algorithms before deciding which one to use for prediction by comparing their results.

Dependencies
============

* Pandas ```pip install pandas```
* Numpy ```pip install numpy```
* Pickle ```pip install pickle```
* Scipy ```pip install scipy```
* Scikit ```pip install -U scikit-learn```

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies

Basic Usage
===========

1. Run ```python learning.py``` to train the model. It will train on the dataset included called 'data.csv'.

2. Once trained you can test the model via ```python checkpe.py YOUR_PE_FILE```. It will output either malicious or legitimate!

That's it!

