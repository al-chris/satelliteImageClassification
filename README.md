# satelliteImageClassification
Python and MATLAB codes for satellite image classification using a convolutional neural network.

The dataset used was gotten from

https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification


# Image Classification Repository

This repository contains Python and MATLAB code for classifying satellite images using a convolutional neural network (CNN). The dataset used is available at [Kaggle: Satellite Image Classification](https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification).

## Project Overview

The project demonstrates how to build and train a CNN to classify satellite images. It includes:

- **Data Preprocessing**: Loading and preparing the dataset for training.
- **Model Architecture**: Defining the CNN structure.
- **Training**: Training the model on the dataset.
- **Evaluation**: Assessing the model's performance on test data.

## Repository Structure

- `LICENSE`: License information.
- `README.md`: Project overview and instructions.
- `satellite.ipynb`: Jupyter Notebook with Python code for training and evaluating the CNN.
- `satellite_images.mlx`: MATLAB Live Script for training and evaluating the CNN.

## Getting Started

To run the code:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/al-chris/satelliteImageClassification.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd satelliteImageClassification
   ```

3. **Install the required Python packages**:

   Ensure you have Python installed, then install the necessary packages:

   ```bash
   pip install -r requirements.txt
   ```

   *Note: The `requirements.txt` file should list all required packages. If it's missing, refer to the imports in `satellite.ipynb` and install the packages manually.*

4. **Download the dataset**:

   Download the dataset from [Kaggle](https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification) and extract it into the project directory.

5. **Run the Jupyter Notebook**:

   ```bash
   jupyter notebook satellite.ipynb
   ```

   Follow the instructions in the notebook to train and evaluate the model.

6. **For MATLAB users**:

   Open `satellite_images.mlx` in MATLAB and run the script to train and evaluate the model.

## Model Architecture

The CNN architecture includes:

- Convolutional layers
- Batch normalization
- ReLU activation functions
- Max pooling layers
- Fully connected (dense) layers

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


This structure is designed to effectively capture spatial hierarchies in the input images.

## Results

After training, the model achieves an accuracy of approximately 98% on the test set.

## Contributing

Contributions are welcome. Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- Dataset: [Kaggle: Satellite Image Classification](https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification)

For any questions or suggestions, please contact [Christopher Aliu](https://github.com/al-chris). 
