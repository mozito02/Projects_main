

# Rotten Tomatoes Movies Rating Prediction

## Overview
This project aims to predict Rotten Tomatoes movie ratings based on critic reviews using machine learning techniques. The dataset used for this project is sourced from Kaggle, which includes information about movies along with critic reviews.

## Dataset
The dataset used for this project can be found on Kaggle: [Rotten Tomatoes movies and critic reviews
(https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset)]
The dataset contains the following features:
- **Feature 1**: Description
- **Feature 2**: Description
- ...

## Methodology
1. **Data Preprocessing**: The dataset was preprocessed to handle missing values, encode categorical variables, and normalize numerical features.
2. **Model Selection**: The Random Forest classifier was chosen for its ability to handle large datasets and its flexibility in capturing complex relationships.
3. **Model Training**: The Random Forest classifier was trained on a subset of the dataset.
4. **Model Evaluation**: The model was evaluated using k-fold cross-validation to assess its performance and generalization ability.
5. **Hyperparameter Tuning**: Hyperparameters of the Random Forest classifier were fine-tuned using techniques such as grid search to improve performance.
6. **Final Model Selection**: The model with the best performance metrics was selected as the final model.

## Results
After training and evaluating the model, the accuracy score achieved was 99.05%. This indicates that the Random Forest classifier performs well in predicting Rotten Tomatoes movie ratings based on critic reviews.

## File Structure
- `dataset.csv`: The raw dataset used for training and evaluation.
- `RTM_prediction.ipynb` : The Jupyter notebook containing all the calculations

## Usage
To reproduce the results of this project:
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.



## Conclusion
This project demonstrates the use of machine learning techniques to predict Rotten Tomatoes movie ratings based on critic reviews. The high accuracy score achieved indicates the effectiveness of the Random Forest classifier in this task. Further improvements could be made by exploring different machine learning algorithms or incorporating additional features.

---

Feel free to customize this README template according to your specific project details and structure. You can add sections such as "Future Work", "Acknowledgments", or "License" as needed.
