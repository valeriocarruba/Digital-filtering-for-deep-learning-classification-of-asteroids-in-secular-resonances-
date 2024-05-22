# Digital-filtering-for-deep-learning-classification-of-asteroids-in-secular-resonances-

We provide a code to obtain images of osculating and filtered resonant arguments for asteroids interacting with secular resonances.  The code will need res_arg_* files with a time series of resonant angles, and a file ast_list with the identification of the asteroids.  It will then apply a Butterworth low-pass filter to extract the long-period frequencies, create images of the osculating and filtered resonant angles, and compute the amplitude and period of libration for the filtered data, saved in the results.txt file.  We provide a set of 10 resonant argument, and a sample ast_list and results.txt files.  You will need to have Python and the numpy, pandas, matplotlib, scipy, and PIL libraries installed on your machine.
To run the code, simply type:

python3 digital_filter.py

More information on this procedure is available in Carruba et al. 2024, MNRAS, under revision.
