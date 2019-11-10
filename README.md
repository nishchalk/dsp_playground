# Digitl Signal Processing Playground

This is a group project for the course 'Foundations of Educational Technology' by Prof.Kaushal Bhagat.
You can find the ppt [here](https://docs.google.com/presentation/d/1Dbipr_cSxPfVV9mUocxhtRKsTAuKE0nQO6y44M568G4/edit?usp=sharing)

This collection of [jupyter](https://jupyter.org/) notebooks for the book "Python for Signal Processing", introduces various topics of [Digital Signal Processing](https://en.wikipedia.org/wiki/Digital_signal_processing). This book is [available as a
blog](http://python-for-signal-processing.blogspot.com) where you can read the formatted notebooks and comment further.

The theory is accompanied by computational examples written in [IPython 3](http://ipython.org/).

The sources of the notebooks, as well as installation and usage instructions can be found on [GitHub](https://github.com/nishchalk/dsp_playground).


##How to create interactive notebooks
1. Write code in jupyter notebook using the [nbinterct](https://www.nbinteract.com/) format.
	* import nbinteract module `from ipywidgets import interact`
	* write the code snippet as a function and give functions for to interact module using `interact(<function_name>, <p1>(:range),<p2>(:range))`
2. Convert the notebook using command `nbinteract <notebook_name>.ipynb`
3. Done!