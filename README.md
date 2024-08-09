# DEEP_LEARNING
Butterfly_Breed_Classification
This project classifies butterfly breeds using a dataset from Kaggle. I applied three different models: a normal Convolutional Neural Network (CNN), VGG16, and an ensemble technique. The goal was to compare their performances in terms of accuracy and validation loss.

**Models Used**
Normal CNN: A simple convolutional model built from scratch.
VGG16: A pre-trained model known for its deep architecture.
Ensemble: A combination of predictions from both the normal CNN and VGG16.
**Results**
VGG16 achieved the best performance with the lowest validation loss.
The normal CNN followed with a slightly higher validation loss.
The Ensemble method performed well but had a higher validation loss than VGG16.
Project Structure
Data Preparation: Loaded and preprocessed the dataset.
Model Training: Trained each model separately.
Prediction and Analysis: Combined predictions into a final dataframe
