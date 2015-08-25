# LNKS-nnet
Neural network models for predicting the membrane potential of retinal ganglion cells to a contrast varying uniform field visual stimulus. 

In the brain, neurons adapt to varying sensory information through successive layers of filtering, thresholds, and nonlinear dynamical processing. These intermediate processes are typically difficult to measure, but recent study has discovered a way to connect the lower level mechanisms to a biophysical model given a ganglion cell's membrane potential (<a href="http://www.sciencedirect.com/science/article/pii/S0896627312000797" target="_blank">Ozuysal and Baccus, Neuron 2012</a>). Here, our goal is to capture the membrane potentials of multiple cells given only the stimulus and spikes recorded from multielectrode arrays (MEAs) so that we can analyze the responses of a population of cells and their intermediate properties simultaneously.


## Dependencies
In order to use and train these models, you will first need to install the following dependencies:

Theano: http://deeplearning.net/software/theano/#download

Keras: https://github.com/fchollet/keras.git

NumPy: http://www.numpy.org/

SciPy: http://www.scipy.org/

LNKS (for loading cell data): https://github.com/baccuslab/LNKS.git

Some of the models may involve the use of layers not found in Keras (noted at the top of the file). If this is the case, simply install these layers from here: https://github.com/anayebi/keras-extra.git.

