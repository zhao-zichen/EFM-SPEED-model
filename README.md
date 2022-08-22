# dynamic-modelling-of-intrinsic-self-healing-polymers-using-deep-learning
This repository contains the codes and models to predict the temporal evolution of cut image and toughness value via the self-healing process.

1) The Energy Functional Minimization (EFM) model is designed to generate a long sequence of predicted cut images based on the initial cut image. 

2) The convolutional neural network (CNN) model called CNN-Toughness is designed to predict the toughness value based on the cut image. 

3) The Self-healing Property Evolution using Energy-functional Dynamical (SPEED) model is designed couples the EFM model with the static CNN model to prediction the evolution of toughness value. A long sequence of predicted healing images can be generated from the EFM model given an initial image. Subsequently, from each image, the corresponding toughness can be predicted by the static model.Then the entire temporal evolution of toughness during self-healing can be obtained.

To run the code, we suggest that users install Anaconda 3 and install the following necessary python packages with the same or higher version to set up a compatible environment: Python 3.6.10; Jupyter-notebook : 5.7.8; Numpy 1.19.2; Tensorflow 2.4.1; OpenCV 4.2.0; Matplotlib 3.3.4; Seaborn 0.10.0; h5py 2.10.0.
