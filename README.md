# dynamic-modelling-of-intrinsic-self-healing-polymers-using-deep-learning
This repository contains the codes and models to predict the temporal evolution of cut image and toughness value via the self-healing process.

1) The Energy Functional Minimization (EFM) model is designed to generate a long sequence of predicted cut images based on the initial cut image. 

2) The convolutional neural network (CNN) model called CNN-Toughness is designed to predict the toughness value based on the cut image. 

3) The Self-healing Property Evolution using Energy-functional Dynamical (SPEED) model is designed couples the EFM model with the static CNN model to prediction the evolution of toughness value. A long sequence of predicted healing images can be generated from the EFM model given an initial image. Subsequently, from each image, the corresponding toughness can be predicted by the static model.Then the entire temporal evolution of toughness during self-healing can be obtained.

