# Neural Network Model for Alphabet Soup Charity Success Prediction

## Overview
This project builds and optimizes a deep learning model to predict the success of charity organizations funded by Alphabet Soup. Using a dataset with various features of these organizations, the goal is to classify whether an organization will be successful based on these attributes.

## Data Preprocessing
- Removed non-beneficial ID columns and handled categorical data with one-hot encoding.
- Grouped rare occurrences in categorical features into an "Other" category to reduce noise.
- Split the data into training and testing sets, and applied feature scaling to optimize model performance.

## Model Design
The deep neural network model was built using TensorFlow and Keras. It includes:
- **Input Layer**: Matches the number of features in the dataset.
- **Hidden Layers**: Two hidden layers using ReLU activation functions.
- **Output Layer**: A Sigmoid activation function for binary classification.

## Model Training and Evaluation
- **Loss Function**: Binary Crossentropy.
- **Optimizer**: Adam.
- Trained on the preprocessed data and evaluated using the test set for accuracy and loss metrics.
- A callback saved the model’s weights every five epochs.

## Optimization
To improve the model, several optimization strategies were used:
- Adjusted the number of neurons and hidden layers.
- Tested different activation functions.
- Fine-tuned the number of training epochs.
- Modified input data through binning and scaling.

Despite these efforts, the target accuracy of over 75% remained elusive.

## Results
- The final model achieved an accuracy of approximately 72%.
- Suggested future improvements include trying alternative models such as Random Forest or Gradient Boosting for potentially better performance.


**Usage**
1. Clone the repository:
git clone https://github.com/yourusername/Neural-Network-Model.git
2. Install the required dependencies
3. Run the Jupyter notebooks in Google Colab or your local environment to explore and execute the code.
