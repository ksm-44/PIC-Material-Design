
# Description for each file
- **training&plot.py**: Data processing, training and postprocessing scripts ;
- **data**: The dataset for this application contains 2000 samples or (**X, Y**) pairs. **X** is the tensor of size 101x101x101 that carries the phase indication for a two-phase heterogeneous material microstructure (or Representative Volume Element). **Y** is a vector of size 12 that represents the effective material properties for the microstructure.
- **saved_model**: The model with best performance on validation set.
- **gallery**: Some figures.

# Overview

<img src="https://github.com/Raocp/3D-ConvNeuralNet-material-property-prediction/blob/master/gallery/clous_pt.png?raw=true" width="400">

> Input **X** for the 3D Convolutional Neural Net, i.e. Cartisian grid carrying phase indication



![](https://github.com/Raocp/3D-ConvNeuralNet-material-property-prediction/blob/master/gallery/NN_archi.png?raw=true)

> Architecture of the 3D Convolutional Neural Net



<img src="https://github.com/Raocp/3D-ConvNeuralNet-material-property-prediction/blob/master/gallery/Pred_vs_Truth_test.png" width="700">

> Achieved prediction versus ground truth on testing data


# Note
- The code was developed based on TensorFlow 1.10.0 and Keras 2.2.4. All the runtime performance are evaluated on GeForce GTX 1080 Ti.
