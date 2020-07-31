# Triplet-net-keras
Implementation of Triplet Neural Network on keras.

My **PyTorch** implmentation with online mining is avaliable [here](https://github.com/KinWaiCheuk/Triplet-net-pytorch)

This code is inspired by adambielski's [github repository](https://github.com/adambielski/siamese-triplet), who implements the Triplet Neural Network on PyTorch, and also this [Kaggle example](https://www.kaggle.com/guichristmann/training-a-triplet-loss-model-on-mnist) by Guilherme Christmann who uses tensorflow to implement the triplet net.

# Dependencies
Tensorflow 1.5

keras 2.2

sklearn 0.19.1

matplotlib 2.2.2

seaborn 0.9

# Instruction
All the required codes are contained inside the jupyter-notebook

# Summary

### The data distribution of raw MNIST dataset
Before using the Triplet Neural Network, the raw date distribution looks like this:

![alt text](https://raw.githubusercontent.com/KinWaiCheuk/Triplet-net-keras/master/train_before.png)
![alt test](https://raw.githubusercontent.com/KinWaiCheuk/Triplet-net-keras/master/test_before.png)

### The data distribution of MNIST dataset after applying Triplet Neural Newtork
After using the Tiplet Neural Network, the dataset forms different clusters according to their classes
![alt test](https://raw.githubusercontent.com/KinWaiCheuk/Triplet-net-keras/master/train_after.png)
![alt_test](https://raw.githubusercontent.com/KinWaiCheuk/Triplet-net-keras/master/test_after.png)
