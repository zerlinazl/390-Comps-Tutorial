# 390-Comps-Tutorial
Code for tutorial report for Occidental College COMP390 Junior Seminar.

To run this code, you must have Librosa, Numpy, and Matplotlib libraries installed. To avoid the process of installing locally, you can open this jupyter notebook in Google Colab. No installs are needed on Colab, the entire notebook can be run as is.

Librosa is a python package to aid in music information retrieval systems. It contains functions to estimate tempo, decompose audio into spectrograms, time warping, and filtering, among others.

To install with pip: 

	python -m pip install -U pip
	pip install librosa

Numpy is an open source library that helps with numerical computation in Python. It is commonly used in matrix mathematics.

To install with pip: 

	pip install numpy

Matplotlib is used to create visualizations and animations in Python. 

Matplotlib can also be installed with pip:

	python -m pip install -U matplotlib

The current versions of all three libraries, which are Librosa 0.10.0, Numpy 1.24.3, and Matplotlib 3.7.1, all work with this code. Older versions are highly likely to work as well.

If you choose to open this file in Google Colab, make sure the folder with the sample audio files is uploaded to the runtime. These files will disappear once the runtime expires. 


### References:
McFee, Brian, Colin Raffel, Dawen Liang, Daniel PW Ellis, Matt McVicar, Eric Battenberg, and Oriol Nieto. “librosa: Audio and music signal analysis in python.” In Proceedings of the 14th python in science conference, pp. 18-25. 2015.
