# satelliteImageClassification
Python and MATLAB codes for satellite image classification using a convolutional neural network.

The dataset used was gotten from

https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification


## Visualization

```
  _________________
 |      Input      |
 |      Data       |
 |_________________|
         |
  _________________
 |     Conv2D      |
 |_________________|
 |   BatchNorm2D   |
 |_________________|
 |      ReLU       |
 |_________________|
 |  MaxPooling2D   |
 |_________________|
         |
  _________________
 |     Conv2D      |
 |_________________|
 |   BatchNorm2D   |
 |_________________|
 |      ReLU       |
 |_________________|
 |  MaxPooling2D   |
 |_________________|
         |
  _________________
 |     Conv2D      |
 |_________________|
 |  BatchNorm2D    |
 |_________________|
 |      ReLU       |
 |_________________|
 |     Flatten     |
 |_________________|
         |
  _________________
 |      Dense      |
 |_________________|
```
