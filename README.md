This repository contains the code and resources for Exercise 4, which focuses on classifying flower images using transfer learning with pre-trained Convolutional Neural Networks (CNNs). The goal is to accurately identify the type of flower depicted in an image by using at least two pre-trained models and adapting them to the task.
Assignment Overview

The exercise involves the following key steps:
- Model Selection: Utilize at least two pre-trained models: YOLOv5 and VGG19.
- Transfer Learning: Adapt the pre-trained models to classify flower images into their respective categories.
- Dataset: The primary image database for training is the Oxford 102 Flower Dataset, available at: https://www.robots.ox.ac.uk/~vgg/data/flowers/102/
- Data Split: Randomly divide the dataset into training (50%), validation (25%), and test (25%) sets. Random split repeated twice.
- Preprocessing: Normalization, resizing to default sizes of the models and adding augmantation to the training set.
- Evaluation: Provide accuracy and cross-entropy graphs for training, validation and test sets across the epochs.
- Performance: The models are at least 70% in at least one of the models.

Repository Contents
- VGG19_Ex4.ipynb: Jupyter Notebook containing the implementation using the VGG19 pre-trained model. Main implementation with random seed = 159.
- VGG19_Ex4_42.ipynb: Jupyter Notebook containing the implementation using the VGG19 pre-trained model. Another implementation of split data with random seed = 42.
- YOLOv5_Ex4.ipynb: Jupyter Notebook containing the implementation using the YOLOv5 pre-trained model.
- YOLOv5_Ex4_42.ipynb: Jupyter Notebook containing the implementation using the VGG19 pre-trained model. Another implementation of split data with random seed = 42.

Code Implementation
The code is written in Python and uses deep learning package PyTorch. The notebooks in this repository demonstrate the following:
1. Loading and preparing the flower image dataset.
2. Implementing the required data split (training, validation, and testing).
3. Pre-processing images for input to the model.
4. Utilising transfer learning with pre-trained VGG19 and YOLOv5 models.
5. Training the models using the prepared dataset.
6. Evaluating the performance of the models.
7. Generating the accuracy and loss graphs.

How to Run
1. Ensure you have Python and the necessary deep learning librarie (PyTorch) installed.
2. Ensure internet connection for data downloading.
3. Open and run the Jupyter Notebooks (VGG19_Ex4.ipynb and YOLOv5_Ex4.ipynb) to reproduce the results.

Notes
- The provided notebooks implement the core functionality of the assignment and may be extended further to improve performance.

Additional Information
The GitHub repository containing the source code for this exercise is located at https://github.com/edenkor150/Exercise-4. The code is written in Jupyter Notebook and there are no other files in the repository.
