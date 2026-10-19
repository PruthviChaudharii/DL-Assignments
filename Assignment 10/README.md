# Assignment 10: Deep Learning Application for Audio Classification with STT and TTS

## Problem Statement

Design and implement a deep learning application for audio classification that incorporates Speech-to-Text (STT) and Text-to-Speech (TTS) using an appropriate deep learning architecture, and evaluate its performance using suitable metrics.

## Objective

To develop an audio classification application that processes audio input, converts speech into text, classifies audio using a suitable deep learning model, and provides spoken output using Text-to-Speech technology.

## Technologies Used

- Python
- Google Colab
- NumPy
- Librosa
- Matplotlib
- TensorFlow / Keras
- Speech-to-Text (STT)
- Text-to-Speech (TTS)
- Scikit-learn

## Methodology

1. Load and explore the audio dataset.
2. Preprocess audio signals and standardize their format.
3. Extract suitable audio features, such as Mel-frequency cepstral coefficients (MFCCs) or Mel spectrograms.
4. Convert speech audio into text using an STT model.
5. Build and train a suitable deep learning architecture for audio classification.
6. Predict the class of the input audio.
7. Convert the classification result or generated response into speech using TTS.
8. Evaluate classification performance using appropriate metrics.
9. Visualize the results and analyze the model's performance.

## Model Architecture

A suitable deep learning architecture, such as a Convolutional Neural Network (CNN), recurrent neural network, or a combination of these, is used for audio classification based on the selected dataset and extracted features.

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

STT performance may additionally be evaluated using Word Error Rate (WER), while TTS output can be assessed for intelligibility and response quality.

## Files

- `Assignment_10_DL.ipynb` — Google Colab notebook containing the implementation, model training, STT and TTS integration, evaluation, and results.

## Conclusion

The application integrates audio classification with Speech-to-Text and Text-to-Speech capabilities. Its classification performance is evaluated using suitable metrics, and the results are analyzed to understand the effectiveness of the implemented deep learning approach.
