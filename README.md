# Python tutorial for expert Matlab users

This repository has pages for a tutorial I am preparing to bring expert Matlab 
users quickly up to speed in using the python scientific stack.

## Date: 14 July 0900-1200

Via Zoom (link to be sent via email)  Contact me if interested in joining: jklymak@uvic.ca

## Scope
1. Basic python, ipython, [jupyter](https://jupyter.org) notebooks
2. Data types
3. Matrices with [Numpy](https://numpy.org), and getting data into numpy (short discussion of [scipy](https://www.scipy.org) as well).
4. Plotting with [Matplotlib](https://matplotlib.org)
5. Structured data with [xarray](https://xarray.pydata.org/)

## "Prerequisites"
Experience with data analysis concepts (but not necessarily in python):
- understand for- and while- loops, conditional statements (if TRUE, else FALSE)
- experience with matrices and (simple) matrix algebra.
- experience with other plotting packages.

## Before class: 

### Have a working jupyter notebook available:

Please have a [jupyter notebook](https://www.dataquest.io/blog/jupyter-notebook-tutorial/) working on your computer before we start class. I strongly recommend installing via [Anaconda](https://www.anaconda.com/products/individual).

After you have installed anaconda, you should be able to go to your computer's shell and type `jupyter notebook` (probably after changing to a work directory) and it will spit out a bunch of verbiage, but will also give you a webpage address to navigate to (usually `https://localhost:8888/tree`); some configurations will just open that webpage for you automatically.  

Now create your first notebook by using the pull-down "New:Python3" This will give a new file `Untitled.ipynb` and a new tab in your web browser.  At the cursor you can type `print('Hello World')`, hit `shift-enter` and the cell should execute and echo "Hello World".

### Download this class using git

From this webpage, you can go to the button `:Code:Clone` and copy the address to your clipboard.

From your shell prompt, somewhere convenient in your file system, you can run `git clone git@github.com:jklymak/PythonFromMatlabTutorial.git`.  This will make a new directory with this tutorial in it called `PythonFromMatlabTutorial`.  

You can `cd PythonFromMatlabTutorial` and run `jupyter notebook` from that directory.  You should be able to open the tutorial in `notebooks/`.

### Have a data set to work on!

In the spririt of "learning by doing" please have a small data set to work on, or a toy model you want to get running.  I will put you in breakout rooms and you can ask questions, and if there is time, we can quickly share our results with one another.