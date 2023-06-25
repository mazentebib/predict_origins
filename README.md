# Predict Origins

This project is conducted by:
- Mazen TEBIB
- Khang Duy LAI

## Project Description

The goal of this project is to develop a robust model for detecting the origin of a writer based on their writing style. The project involves data exploration, preprocessing, feature extraction, model selection, and hyperparameter tuning.

## Repository Contents

The code provided in this repository includes:

- **Data Exploration**: Understanding the data and its features.
- **Data Preprocessing**: Cleaning raw texts, using TF-IDF Vectorizer for feature extraction, encoding labels, and extracting features. 

- **Feature Extraction**: The features extraction process involves both lexical and syntactic features. Lexical features include total number of words, characters, alphabetic characters, upper-case characters, syllables, average word length, average sentence length by characters and words, and ratio of unique words. Syntactic features include frequency of special characters, punctuations, functional words, part of speech tags, and number of sentences.

- **Model Selection**: Testing several models including Nearest Neighbors, Linear SVC, Random Forest, Kmeans, and GaussianNB. The best model is selected based on the overall score.
                        A cascade method is also applied to see if there are any improvements.
- **Hyperparameter Tuning**: Optimizing the performance of the selected model.

## Libraries Used

The project uses the following Python libraries:

- pandas
- numpy
- sklearn
- matplotlib


## Future Work

- Optimize the model for better performance.
- Explore other feature extraction techniques and models.
- Use a larger and more diverse dataset for better generalization.

