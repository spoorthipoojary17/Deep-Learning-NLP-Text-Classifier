# Deep Learning NLP Text Classifier – SMS Spam Detection

## Project Overview
This project uses Deep Learning and Natural Language Processing (NLP) to classify SMS messages as Spam or Ham (Not Spam).

A TensorFlow neural network is trained using TF-IDF text vectorization to identify spam messages.

## Technologies Used
- Python
- Google Colab
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- TF-IDF Vectorization

## Project Workflow
1. Dataset collection
2. Data exploration and preprocessing
3. Duplicate removal and text cleaning
4. TF-IDF vectorization
5. Training and testing data splitting
6. Deep Learning Neural Network construction
7. Batch Normalization and Dropout
8. Model training with Early Stopping
9. Accuracy and loss visualization
10. Model evaluation and sample predictions

## Model Architecture
- Dense layer (256 neurons)
- Batch Normalization
- Dropout (0.4)
- Dense layer (128 neurons)
- Batch Normalization
- Dropout (0.3)
- Dense layer (64 neurons)
- Dropout (0.2)
- Output layer (Sigmoid activation)

## Model Performance

| Metric | Result |
|---|---:|
| Test Accuracy | 97.97% |
| ROC-AUC | 0.9914 |
| Spam Precision | 0.98 |
| Spam Recall | 0.85 |
| Spam F1-score | 0.91 |

## Sample Predictions
The model successfully classifies new SMS messages into:
- Spam
- Ham (Not Spam)

It also displays prediction confidence scores.

## Dataset
SMS Spam Collection Dataset from the UCI Machine Learning Repository.

## Project Files
- `Deep_Learning_NLP_Text_Classifier.ipynb` – Complete implementation, training, evaluation, graphs and predictions.

## Conclusion
This project demonstrates how Deep Learning and NLP techniques can be used to detect spam messages automatically. The trained model achieved 97.97% test accuracy on unseen data.

## Author
Spoorthi Poojary
