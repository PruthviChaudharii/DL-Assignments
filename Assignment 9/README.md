# Assignment 9: Vision Transformer (ViT) vs CNN for Image Classification

## Problem Statement

Perform image classification using a pre-trained Vision Transformer (ViT) model and compare its performance with a CNN model.

## Objective

To implement image classification using a pre-trained Vision Transformer (ViT), compare it with a Convolutional Neural Network (CNN), and analyze their performance using suitable evaluation metrics.

## Dataset

A suitable image classification dataset is used to train and evaluate both models. Examples include CIFAR-10 or another appropriate sample image dataset.

## Technologies Used

- Python
- Google Colab
- PyTorch
- Torchvision
- Hugging Face Transformers
- NumPy
- Matplotlib
- Scikit-learn

## Models Implemented

### 1. Vision Transformer (ViT)

A pre-trained Vision Transformer is adapted for image classification. It divides images into patches and uses self-attention mechanisms to learn relationships between them.

### 2. Convolutional Neural Network (CNN)

A CNN model is implemented or fine-tuned for image classification. It uses convolutional and pooling layers to learn spatial features from images.

## Methodology

1. Load and explore the image dataset.
2. Preprocess and normalize the images.
3. Split the dataset into training, validation and testing sets.
4. Load a pre-trained ViT model and adapt it to the selected classes.
5. Implement or load a CNN model for the same classification task.
6. Train or fine-tune both models using comparable settings.
7. Evaluate both models on the same test dataset.
8. Compare their classification performance and computational requirements.
9. Visualize the results using graphs and a comparison table.

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Training Time

## Performance Comparison

The ViT and CNN models are compared using the same dataset and test split. Their accuracy, evaluation metrics and training time are analyzed to understand their strengths and limitations.

## Files

- `Assignment_9_DL.ipynb` — Jupyter Notebook containing the ViT implementation, CNN implementation, evaluation, comparison and results.

## Conclusion

The assignment compares a pre-trained Vision Transformer with a CNN for image classification. The results are used to analyze differences in classification performance, computational cost and feature-learning approaches.
