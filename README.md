# EEG Emotion Classification with Deep Learning

## Overview
This repository contains Python code for performing emotion classification using EEG (Electroencephalogram) data. Emotion classification from EEG signals is a crucial application in neuroscience and human-computer interaction. The code leverages deep learning techniques to analyze EEG data and predict emotional states.

## Key Features

### Data Loading and Preprocessing:
- **Loads EEG Data**: Imports EEG data from a CSV file containing features extracted from EEG signals.
- **Label Conversion**: Converts emotion labels such as 'NEGATIVE', 'NEUTRAL', and 'POSITIVE' into numerical values (0, 1, 2) for classification.

### Data Visualization:
- **Pie Chart**: Displays the distribution of emotions in the dataset.
- **Time-Series Plot**: Visualizes EEG signals over time.
- **Power Spectral Density (PSD) Plot**: Conducts spectral analysis of EEG signals.
- **Correlation Heatmap**: Understands feature correlations within the data.
- **t-SNE Visualization**: Applies t-Distributed Stochastic Neighbor Embedding for dimensionality reduction.

### Feature Significance Analysis:
- **Statistical Tests**: Performs t-tests to identify significant features for each emotion category.
- **Visualization of Results**: Uses bar charts to demonstrate which features contribute most to emotion prediction.

### Advanced Preprocessing:
- **Normalization**: Applies z-score normalization to feature data.
- **Data Splitting**: Splits the dataset into training and testing sets.

### Deep Learning Model:
- **Model Architecture**: Builds a deep neural network with multiple dense layers, ReLU activation functions, and dropout layers.
- **Compilation**: Uses the Adam optimizer and sparse categorical cross-entropy loss for model compilation.
- **Training**: Trains the model on the training data with validation, tracking accuracy during the process.

### Model Evaluation:
- **Testing**: Evaluates the trained model on the testing dataset, reporting the accuracy of emotion classification.
- **Performance Metrics**: Generates a confusion matrix and a classification report for comprehensive assessment.

### Random Sample Visualization:
- **Sample Prediction**: Selects a random EEG sample from the testing dataset and predicts its emotion label.
- **Signal Plotting**: Plots EEG signals from the selected sample.

## Getting Started
For detailed usage instructions and explanations, please refer to the code comments and accompanying documentation in the repository.

## Customization
Feel free to customize and extend this code for your specific EEG emotion classification projects.
