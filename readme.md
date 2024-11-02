# Me vs. Not-Me Binary Classification Using Logistic Regression

## Overview
This project originated as a personal endeavor during my initial exploration into machine learning. The goal was to apply fundamental concepts by implementing a simple binary classification task using logistic regression. Specifically, I wanted to experiment with classifying images of myself versus non-self images to observe the performance and limitations of this basic model. This project provided a hands-on opportunity to deepen my understanding of logistic regression and its application in image-based classification tasks.

This project involves building and evaluating a binary classification model using the logistic regression function to distinguish between "me" (collected image of me) and "not-me" (images that do not contain my images, such as a dog or other persons). Logistic regression is a simple yet powerful algorithm suitable for binary classification problems, making it an effective starting point for understanding the basics of machine learning.

## Project Structure
- `notebooks/`: Jupyter notebooks that outline data exploration, preprocessing, model training, and evaluation.
- `README.md`: This file, providing an overview and guidance for the project.

## Key Features
- **Binary Classification**: Classifies input images as either "me" or "not-me."
- **Logistic Regression**: Utilizes the logistic function to predict the probability of the input belonging to the "me" class.
- **Model Evaluation**: Includes metrics such as accuracy, precision, recall, and ROC-AUC score for comprehensive model performance analysis.

## Installation and Setup
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/me-notme-classification.git
    cd me-notme-classification
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook or script:
    ```bash
    jupyter notebook notebooks/me_notme_classification.ipynb
    ```

## Data Preparation
- The dataset were  structured into separate folders for "Training dataset" and "Test dataset" . Each folder consist of  within "me" and "not me" directory. Due to privacy considerations, the dataset has not been uploaded online.

## Model Details
- **Algorithm**: Logistic Regression using a sigmoid function to predict the probability of the input being "me."
- **Feature Extraction**: Image data is converted into feature vectors suitable for logistic regression.
- **Training**: The model is trained with a labeled dataset that includes examples of "me" as '1'  and "not-me"  as '0' images.
- **Loss Function**: Binary cross-entropy is used as the loss function to guide optimization.


## Results
- **Training Accuracy**: Achieved 99.66% on the training dataset.
- **Test Accuracy**: Achieved 53.94% on the test dataset.

## Visualizations
- **Plot learning curve (with costs)**: Displayed to visualize cost with learning rate over training epochs.
- **learning rate with different values**: display cost with three different values of alpha (0.01, 0.001,0.001) over training epoch .



