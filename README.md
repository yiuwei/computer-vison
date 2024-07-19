# Computer Vision Project

This project implements the neural network models to classify handwriting digits from the MNIST database. The neural network is a technique in AI that comprises multiple layers of connected units to extract information and conduct image classification. The project will utilize Python, Tensorflow, and Computer Vision techniques to create neural networks, and to maximize the model accuracy. 

**Neural Networks**

The neural network model incorporates machine learning and artificial intelligence to train the computers to perform tasks that mimic humans. The project will utilize several models, including convolutional neural networks and dense neural networks to evaluate the model training, validation, and testing accuracy. 

**Convolutional Neural Network**

| Layer Type          | Output Shape     | Parameters    |
|---------------------|------------------|---------------|
| Conv (4x4x32)       | 28x28x32         | 544           |
| Max Pooling (2x2)   | 14x14x32         | 0             |
| Conv (3x3x64)       | 14x14x64         | 18,496        |
| Max Pooling (2x2)   | 7x7x64           | 0             |
| Flatten             | 3136             | 0             |
| Dense (64)          | 64               | 200,768       |
| Dense (10)          | 10               | 650           |

**Dense Neural Network**

| Layer Type          | Output Shape     | Parameters    |
|---------------------|------------------|---------------|
| Flatten (28,28,1)   | 784              | 0             |
| Dense (512)         | 512              | 401,920       |
| Dense (256)         | 256              | 131,328       |
| Dense (128)         | 128              | 32,896        |
| Dense (10)          | 10               | 1,290         |
