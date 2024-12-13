# Deep Learning for Multi-Class Classification Using CIFAR-10

This project involves designing and implementing multiple Deep Neural Network (DNN) architectures to classify images from the CIFAR-10 dataset into 10 different categories. The objective was to evaluate and fine-tune hyperparameters, including the number of layers, activation functions, and optimizers, to achieve better performance than a baseline model.

---

## Project Overview

### Dataset
The CIFAR-10 dataset consists of:
- **50,000 training images** (32x32 color images)
- **10,000 testing images**
- **10 classes**: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

For more details about the dataset, visit the [CIFAR-10 documentation](https://www.cs.toronto.edu/~kriz/cifar.html).

### Objective
The objective of this project is to:
1. Build a baseline DNN model for image classification.
2. Design and fine-tune two additional DNN models with optimized hyperparameters for improved performance.

---

## Tools and Libraries
- **Python**
- **Keras**
- **TensorFlow**

---

## Models

1. **Baseline Model**:
   - A simple DNN with a few layers and basic hyperparameters.
   - Used to establish a reference for comparison.

2. **Fine-tuned Model 1**:
   - Optimized number of layers, neurons, and activation functions for improved classification performance.

3. **Fine-tuned Model 2**:
   - Adjusted optimizer, learning rate, and regularization techniques to further enhance accuracy.

### Metrics
The models are evaluated using **accuracy**, which measures the proportion of correctly classified images.

---

## Key Features
- **Baseline Performance**: Evaluate initial results to establish a reference point.
- **Hyperparameter Optimization**: Experiment with different layers, neurons, activation functions, loss functions, and optimizers.
- **Comparison**: Compare the accuracy of the baseline and fine-tuned models.

---

## Results
The performance of the three models is summarized below:
1. **Baseline Model**: [Insert accuracy percentage]
2. **Fine-tuned Model 1**: [Insert accuracy percentage]
3. **Fine-tuned Model 2**: [Insert accuracy percentage]

Please refer to the Jupyter notebook for detailed results and plots.

---

## File Structure
- `Project03.ipynb`: The Jupyter notebook containing the implementation of all models.
- `README.md`: This file, providing an overview of the project.
- `requirements.txt`: A list of required Python libraries.

---

## Instructions to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Raunav/CIFAR10-MultiClass-Classification.git
2. Install dependencies:
   pip install -r requirements.txt
3. Open the notebook:
   jupyter notebook CIFAR-10.ipynb
4. Run the cells in the notebook to train and evaluate the models.

   
