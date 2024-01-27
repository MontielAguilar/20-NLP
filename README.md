
# NLP (Natural Language Processing) for URL Spam Classification
This repository contains a Natural Language Processing (NLP) project for the classification of spam in URLs. It employs a Support Vector Machine (SVM) model with text processing techniques to distinguish between spam and non-spam URLs.

## Project Structure
main.py: Contains the main code that defines, processes, and trains the SVM model.
requirements.txt: List of dependencies needed to run the project.
Requirements
Make sure to have all dependencies installed. You can do this by executing the following command:

## bash

pip install -r requirements.txt

## Data Processing
### Data Reading
Data is loaded from the link provided in the main.py file.

### Data Processing
Categorical to numeric transformation is performed, and duplicate values are eliminated.

### Text Processing
Removal of Non-Alphabetic Characters and Whitespaces
URLs are cleaned by removing non-alphabetic characters and whitespaces.

## Tokenization and Lemmatization
URLs are tokenized, and words are lemmatized.

## Modeling
### Word Cloud
A word cloud is generated to visualize frequent terms.

### TF-IDF Vectorization
URLs are converted to numerical vectors using TF-IDF.

### SVM and Model Training
Initialization and Training of the Model: An SVM with an rbf kernel, C=10, and gamma=0.1 is used to train the model.

## Model Predictions
Predictions are made on the test dataset.

## Evaluation
Model Accuracy
The model's accuracy is calculated using the test dataset.

## Save Model
The model is saved in a file named "ruta.sav" using the pickle library.

## Hyperparameterization (Optional)
Code for hyperparameterization using GridSearchCV is provided, although it has not been executed due to temporary resource constraints.

