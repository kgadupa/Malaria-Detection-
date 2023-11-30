# Malaria Detection: Custom Model vs VGG-16

This repository presents a comparison between a custom deep learning model for malaria detection and the pre-trained VGG-16 model. The primary goal is to evaluate and compare the performance of these models in detecting malaria parasites in microscopic images of blood smears.

## Overview

Malaria is a life-threatening disease caused by parasites that are transmitted to humans through the bites of infected mosquitoes. Microscopic examination of blood smears remains one of the most widely used methods for diagnosing malaria. This project focuses on leveraging deep learning models to automate this detection process.

## Dataset

The dataset used for training and evaluation consists of thousands of microscopic images of blood smears infected and uninfected with malaria parasites. The dataset is preprocessed and divided into training, validation, and test sets.

## Custom Model

The custom deep learning model architecture is designed specifically for malaria detection using convolutional neural networks (CNNs). The model architecture is implemented using TensorFlow/Keras and trained on the provided dataset.

## VGG-16 Model

The VGG-16 model, a well-known convolutional neural network architecture, is used as a benchmark for comparison purposes. The pre-trained VGG-16 model is fine-tuned on the same dataset and evaluated for malaria detection.

## Comparison

The comparison is based on several evaluation metrics including accuracy, precision, recall, F1-score, and area under the ROC curve (AUC-ROC). Both models are evaluated on the test set to assess their performance in correctly identifying malaria-infected samples.

## Results

The results of the comparison are presented in detail, showcasing the performance metrics of both models side by side. Additionally, visualizations such as confusion matrices and ROC curves are provided to illustrate the models' performance.

## Usage

1. **Clone the Repository**:
git clone https://github.com/kgadupa/malaria-detection-model-comparison.git


2. **Dataset Preparation**:
- Download the dataset or provide instructions on how to obtain it.
- Organize the dataset into appropriate directories (infected/uninfected) for training and testing.

3. **Model Training and Evaluation**:
- Follow the instructions in the provided notebooks or scripts to train and evaluate the custom model and VGG-16.
- Ensure necessary dependencies are installed (TensorFlow, Keras, etc.).

4. **Review Results**:
- Explore the evaluation metrics, visualizations, and analysis presented in the repository to understand the comparison between the models.

## Conclusion

Summarize the findings of the comparison and discuss any insights gained from the evaluation. Highlight strengths and limitations of both models and potential areas for improvement.

---

Feel free to adjust and expand upon this README to include more details about the models, methodology, and any additional findings or insights from your comparison. Additionally, ensure that you provide proper citations and credit to any sources or references used in your project.
