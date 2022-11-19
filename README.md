# Comment-Toxicity-Model-using-LSTM


Problem Statement:
“To build a multi-headed model that’s capable of detecting different 
types of toxicity like threats, obscenity, insults, and identity-based hate.”

Work Flow
Toxic Comment Classifier is a competition that has been organized by 
Jigsaw/Conversation AI and hosted on Kaggle. The data set for building 
the classification model was acquired from the competition site and it 
included the training set as well as the test set. The steps elaborated 
in the workflow below will describe the entire process from Data Pre-Processing to Model Testing.

File1: comment_toxicity_lstm.py

PART 1: Setup and Data Loading

PART 2: Prepare Comments

PART 3: Build a Deep Learning Model

PART 4: Make Predictions

PART 5: Evaluate the Model

PART 6: Build a Deep Learning Gradio App

File2: lstm_better.py

Data Exploration, Data Pre-processing, and Feature Engineering
Step 1: Checking for missing values.

Step 2: Text Normalization.

Removing Characters in between Text.
Removing Repeated Characters.
Converting data to lower-case.
Removing Punctuation.
Removing unnecessary white spaces in between words.
Removing “\n”.
Removing Non-English characters.

Step 3: Lemmatization.

Step 4: Stopwords Removal.

Step 5: Tokenization, Indexing, and Index Representation.

Step 6: Padding.

Model Creation & Model Assessment

Step 1: Split Training Data into Train-Set and Validation-Set.

Step 2: Import fastText’s pre-trained word embeddings.

Step 3: Model Creation (LSTM).

Step 4: Evaluate the Model Accuracy and Model Loss during the 
training phase.

Step 6: Calculating Model Accuracy using Test-set.

Step 7: Build a Deep Learning Gradio App.
