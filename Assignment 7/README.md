# Assignment 7: Transfer Learning for Image Classification

## Problem Statement

Implement Transfer Learning using pre-trained AlexNet, VGG16, ResNet50 and EfficientNetB0 models for image classification and compare their performance.

## Objective

To implement and compare four pre-trained deep learning architectures using transfer learning for image classification and evaluate their performance using suitable metrics.

## Models Implemented

1. **AlexNet** — A CNN architecture known for its early use in large-scale image classification.
2. **VGG16** — A deep CNN using small convolutional filters.
3. **ResNet50** — A residual network that uses skip connections to train deeper networks.
4. **EfficientNetB0** — An efficient CNN architecture that balances network depth, width and input resolution.

## Technologies Used

- Python
- Google Colab
- TensorFlow / Keras
- PyTorch / Torchvision (if used for AlexNet)
- NumPy
- Matplotlib
- Scikit-learn

## Methodology

1. Load and explore the image dataset.
2. Preprocess images and resize them to the required input dimensions.
3. Split the dataset into training, validation and testing sets.
4. Load the pre-trained models with their appropriate weights.
5. Replace or adapt the classification layers for the selected dataset.
6. Train the models using transfer learning.
7. Evaluate each model on the test dataset.
8. Compare the models using evaluation metrics and training time.
9. Visualize the performance using suitable graphs and tables.

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Training Time

## Performance Comparison

The four models are compared based on classification performance, computational requirements and training behavior. The results help identify the most suitable architecture for the selected image classification task.

## Files

- `Assignment_7_DL.ipynb` — Jupyter Notebook containing model implementation, training, evaluation, performance comparison and results.

## Conclusion

The assignment demonstrates transfer learning using AlexNet, VGG16, ResNet50 and EfficientNetB0. Their performance is compared to understand the trade-offs between classification accuracy, computational cost and training efficiency.
