# Speech Emotion Recognition from Audio
This project aims to recognize emotions from audio files using machine learning algorithms. The dataset used is the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS).


## Dataset
The dataset used for this project can be downloaded from [RAVDESS](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio).

## Usage
1. Clone this repository.
2. Download the dataset and place it in the desired directory.
3. Update the Ravdess variable with the path to the dataset.
4. Run the code in your Python environment.

## Description of the Code
The code performs the following tasks
1. Import necessary libraries.
2. Mount Google Drive (only required if you're running the code on Google Colab and have the dataset stored in Google Drive).
3. Define the path to the RAVDESS dataset.
4. Create a DataFrame containing the file paths and corresponding emotions.
5. Visualize the count of emotions in the dataset.
6. Create waveplots and spectrograms for different emotions.
7. Define data augmentation functions: noise, stretch, shift, and pitch.
8. Define the extract_feature function that extracts MFCC, Chroma, and Mel features from an audio file.
9. Define the load_data function that splits the dataset into training and testing sets.
10. Train a Multi-Layer Perceptron (MLP) Classifier on the training set.
11. Evaluate the trained model on the test set using a confusion matrix, classification report, and accuracy score.

## Output
The output will show
1. The count of emotions in the dataset.
2. Waveplots and spectrograms for different emotions.
3. A confusion matrix for the trained MLP Classifier.
4. A classification report for the trained MLP Classifier.
5. The accuracy score of the trained MLP Classifier.
