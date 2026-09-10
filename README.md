# Painting Genre Recognition

This project explores the use of Convolutional Neural Networks (CNNs) for automatic painting genre recognition from images.

The goal is to build and evaluate a complete image classification pipeline, from dataset preparation and class balancing to neural network training and experimentation with different model configurations.

## Project Structure

The repository is organized as a sequence of Jupyter notebooks:

- `1_Dataset.ipynb`  
  Dataset exploration, preprocessing and preparation.

- `2_Dataset_Balancing.ipynb`  
  Analysis of class imbalance and dataset balancing.

- `3_CNN.ipynb`  
  Baseline convolutional neural network implementation and training.

- `4_CNN_unbalanced.ipynb`  
  Experiments performed on the original unbalanced dataset.

- `5_CNN_balanced_with_dropout_on_100_epochs.ipynb`  
  Training on the balanced dataset with dropout regularization and an extended training schedule.

## Main Topics

The project covers:

- Image preprocessing
- Dataset preparation
- Class imbalance analysis
- Dataset balancing
- Convolutional Neural Networks
- Dropout regularization
- Model training and evaluation
- Comparison of different experimental configurations

## Motivation

Painting genre recognition is an interesting computer vision problem because visual categories can share similar colors, shapes and compositions.

The project was therefore an opportunity to investigate how convolutional neural networks learn visual representations and how factors such as class imbalance and regularization affect classification performance.

## Technologies

- Python
- Jupyter Notebook
- Deep Learning
- Convolutional Neural Networks
- Computer Vision

## Experimental Approach

Several configurations were explored rather than relying on a single model.

In particular, the project compares:

1. A baseline CNN.
2. Training on the original imbalanced dataset.
3. Training after dataset balancing.
4. A regularized CNN using dropout.
5. Longer training runs to study model convergence.

This experimental approach helped evaluate the impact of both dataset composition and architectural choices on the resulting classifier.

## Author

Riccardo Orrù
