# Computer-Vision
## Image Labelling - Linear Classification

This GitHub repository contains the code and documentation for the "Image Labelling - Linear Classification" assignment. In this assignment, I will work with the Chars74K dataset of characters from the English alphabet, specifically focusing on images of characters '4', 'A', 'u', and the digit 'H'. I will train binary and multiclass linear classifiers using scikit-learn and evaluate their performance using various metrics.

### Dataset
You can download the Chars74K dataset from [this link](http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/). Look for the archive called `EnglishImg.tgz`, a gzipped tar archive. You can extract it using tools like gzip or 7-zip. This dataset includes images of characters and digits organized into subdirectories for each character in the Latin alphabet (both upper and lower case), as well as for the digits.

### Getting Started
1. Download and extract the dataset.
2. Load the images into numpy matrices using scikit-learn image processing tools.
3. Organize the data into training, validation, and test sets.
4. Read, preprocess, and resize the images, converting them to grayscale.

### Assignment Tasks

#### 1. Binary Classifiers
- Train a logistic regression classifier to distinguish grayscale images of the letters '4' and 'A'.
- Organize the data into training, validation, and test sets.
- Calculate the confusion matrix and other metrics (accuracy, recall, precision) without using scikit-learn functions.
- Provide an explanation of the results.

#### 2. Multiclass Classifier
- Train a multiclass logistic regression model to classify grayscale images into four classes: '4', 'A', 'u', and 'H'.
- Reorganize the data into training, validation, and test sets.
- Calculate the confusion matrix and other metrics (accuracy, average recall, average precision, F1 score) without using scikit-learn functions.
- Discuss the classifier's performance, including insights into class difficulty and potential confusion.
