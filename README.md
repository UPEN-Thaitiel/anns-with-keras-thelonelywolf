[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WIfrVNj6)
# ANNs-with-Keras

This repository contains a set of Jupyter Notebooks designed to introduce and practice the implementation of Artificial Neural Networks (ANNs) using Keras and TensorFlow. Each notebook covers a different problem type and scenario to help students understand the key components of neural network modeling.

## Repository Structure

### 1. `Keras-Syntax-Basics.ipynb`
This notebook demonstrates the foundational syntax for building ANNs in Keras. It walks through the process of solving a **regression problem** using the dataset `fake_reg.csv`, which is included in the repository. The exercise includes:

- Data preprocessing
- Model architecture definition
- Compilation and training
- Evaluation and prediction

### 2. `Keras-Classification.ipynb`
This notebook applies Keras to a **binary classification problem** using the dataset `cancer_classification.csv`. Three modeling strategies are explored:

- **Scenario A**: Train a model for 600 epochs without regularization
- **Scenario B**: Use **early stopping** to prevent overfitting and save the best model
- **Scenario C**: Add **dropout layers with 50% rate** to mitigate overfitting

Each scenario includes training, evaluation, and discussion of model performance.

### 3. `Keras-Exercise.ipynb`
This notebook is a guided challenge that must be completed by the user. Using the dataset `lending_club_info.csv`, students are expected to:

- Follow markdown instructions embedded in the notebook
- Perform all necessary preprocessing
- Build and train a neural network
- Ensure the output matches the expected result described in the markdown (100% match required)

## Datasets
All datasets used in the notebooks are included in the repository:
- `fake_reg.csv`
- `cancer_classification.csv`
- `lending_club_info.csv`

