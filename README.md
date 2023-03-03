# Summary

This Python code processes a dataset of Green's functions and creates arrays of Green's functions. It then compresses the arrays to (sample*sample) size and saves them as images.

# Requirements

This code requires the following libraries to be installed:

numpy
pandas
matplotlib
scipy
skimage


# Installation

To install the required libraries, you can use pip:
pip install numpy pandas matplotlib scipy scikit-image

# Usage

To use the code, you need to have a dataset of Green's functions in a CSV file named "Gloc.out". The CSV file should have the following format:

The first row should contain the column names.
The first column should contain the type of Green's function (ret, les, or tv).
The second and third columns should contain the time indices.
The fourth column should contain the real part of the Green's function.
The fifth column should contain the imaginary part of the Green's function.
To run the code, simply execute the Python file "greens_functions.py". The code will create compressed images of the Green's functions and save them in the same directory as the input file.
