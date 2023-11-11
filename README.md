# Particle Detection Neural Network

**Authors:** Joey Hernandez, Danny Chang

## Background

The exploration of particle physics has driven our understanding of the universe's fundamental components. Detecting and identifying subatomic particles is crucial for this endeavor. However, as particle accelerators generate vast amounts of data, traditional analytical methods face challenges. Neural networks, inspired by the human brain, have emerged as powerful tools in particle detection. They excel at recognizing complex patterns and making predictions from large datasets, offering innovative approaches to sift through noise and identify signals of novel occurrences.

## Objective

This project aims to design and implement a neural network-based system for detecting and predicting the existence of new particles in experimental data. The system addresses the limitations of manual analysis techniques by providing a scalable, automated alternative, enhancing accuracy and reliability in particle identification. By leveraging the predictive power of neural networks, the project seeks to facilitate the discovery of particles beyond the Standard Model.

## Data Inspection

Before modeling, a thorough inspection of the dataset was conducted. The balanced nature of the dataset, free from missing values, ensures a symmetrical representation of both outcomes. This balance simplifies model evaluation and reduces the need for additional data processing techniques.

## Modeling

### Dense Neural Network (DNN)

Utilizing the TensorFlow framework with its Keras API, a Dense Neural Network (DNN) was designed. The architecture includes an input layer, two hidden layers with ReLU activation, and an output layer with a sigmoid activation for binary classification. The model prevents overfitting through potential future iterations with techniques like dropout and regularization.

### Model Design and Training Specifications

The model, configured to potentially iterate through 1000 epochs, employs early stopping to balance underfitting and overfitting. The classification report, confusion matrix, and ROC curve analysis demonstrate the model's robust performance.

## Results

The DNN achieved an accuracy of 0.88 across a test dataset of 1,400,000 samples. Precision, recall, and F1-scores indicate a balanced harmony between the model's ability to identify true positives and true negatives. The AUC of 0.96 in the ROC curve reinforces the model's excellent discriminative ability.

## Conclusion

This research represents a significant stride in automating and refining particle detection through neural networks. The model's performance suggests its potential in advancing our understanding of the universe by efficiently sifting through extensive datasets. The success of the neural network hints at the immense potential of machine learning applications in particle physics research.

## Appendix

The provided code and dataset allow for further exploration and understanding of the implemented neural network.