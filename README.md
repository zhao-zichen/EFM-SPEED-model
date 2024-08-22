# dynamic-modeling-of-intrinsic-self-healing-polymers-using-deep-learning
This repository contains the codes and models to predict the temporal evolution of cut image and toughness value via the self-healing process.

1) The Energy Functional Minimization (EFM) model is designed to generate a long sequence of predicted cut images based on the initial cut image. 

2) The convolutional neural network (CNN) model called CNN-Toughness is designed to predict the toughness value based on the cut image. 

3) The Self-healing Property Evolution using Energy-functional Dynamical (SPEED) model is designed couples the EFM model with the static CNN model to prediction the evolution of toughness value. A long sequence of predicted healing images can be generated from the EFM model given an initial image. Subsequently, from each image, the corresponding toughness can be predicted by the static model.Then the entire temporal evolution of toughness during self-healing can be obtained.

To run the code, we suggest that users install Anaconda 3 and install the following necessary python packages with the same or higher version to set up a compatible environment: python 3.6.10; jupyter-notebook : 5.7.8; numpy 1.19.2; tensorflow 2.4.1; opencv 4.2.0; matplotlib 3.3.4; seaborn 0.10.0; h5py 2.10.0.

The numpy file of (10) cut image examples can be downloaded from https://drive.google.com/file/d/1yatogRrH1uLS4zuwSe0GAnUtX-xdF3NE/view?usp=sharing.
