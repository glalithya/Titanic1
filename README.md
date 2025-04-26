# Titanic Survival Prediction

This project builds a machine learning model to predict if a passenger survived the Titanic disaster based on various features like age, gender, ticket class, fare, etc.

## Steps followed:

- Data Cleaning (handling missing values)
- Feature Engineering (encoding categorical variables, normalization)
- Model Building (Random Forest Classifier)
- Hyperparameter Tuning using GridSearchCV
- Evaluation (Confusion Matrix, Accuracy, Precision, Recall)

## Technologies Used:
- Python 3
- pandas, scikit-learn, matplotlib, seaborn

## How to Run:
1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
2. Place the `tested.csv` in the project folder.
3. Run the model:
    ```bash
    python titanic_model.py
    ```

---

*Model achieved an accuracy of ~80% depending on random seed and train-test split.*
