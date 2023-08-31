# deep-learning-challenge

I worked on this challenge completely on my own. The deep learning first model is the notebook I used to first find the model, and the alphabetsoupcharity.h5 file is the model from that notebook. The second notebook, alphabetsoupcharity_optimization.ipynb, is my attempt at finding a model that has greater than 75% accuracy. The best model I found from that attemp is the alphabetsoupcharity_optimization.h5 file.

I used code from several resources to complete this challenge. First, I used the byo_neural_network notebook and over_the_moon_solution to see the basics of how to write a neural network, and those are used when making my neural networks. I also used the stack overflow link "https://stackoverflow.com/questions/28272137/pandas-how-to-filter-a-series"

to see how to filter a series, and this was used in my preprocessing of the data to filter out certain values. This was used in both of the notebooks. 

Then, I used the "tune_up_solution" notebook to see how to use the keras tuner. I largely copied the cells from that notebook with minor changes, such as changing the max number of layers. That code appears in cells 27 through 37 of my alphabetsoupcharity_optimization.ipynb notebook.