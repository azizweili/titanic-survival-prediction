# Titanic Survival Prediction

## Project Description
This project is a **machine learning model** that predicts the survival of passengers on the Titanic based on their personal information (such as age, sex, class, and other features). The model uses historical Titanic data to learn patterns and make predictions.

## Dataset
The dataset is sourced from the **Kaggle Titanic competition** and contains the following key features:  
- `PassengerId`: Unique identifier for each passenger  
- `Pclass`: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- `Name`, `Sex`, `Age`  
- `SibSp`: Number of siblings/spouses aboard  
- `Parch`: Number of parents/children aboard  
- `Ticket`: Ticket number  
- `Fare`: Passenger fare  
- `Cabin`: Cabin number  
- `Embarked`: Port of embarkation  

## Technologies Used
- Python 3  
- Pandas & NumPy for data preprocessing  
- Scikit-learn for model building and evaluation  
- Matplotlib & Seaborn for data visualization  

## Data Preprocessing
- Handle missing values (`NaN`) in `Age`, `Cabin`, and `Embarked` columns  
- Encode categorical variables such as `Sex` and `Embarked`  
- Feature scaling for numerical columns (if required)  

## Modeling
- **Logistic Regression** (primary model)  
- Other models can be experimented with, such as Decision Trees or Random Forests  
- Train-test split (80% train, 20% test) with `random_state=42` for reproducibility  

## Evaluation Metrics
- Accuracy  
- Precision, Recall, and F1-Score  
- Confusion Matrix  

## Usage
1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/titanic-survival-prediction.git
   ```
   
2. Install dependencies:
   pip install -r requirements.txt
3. Run the notebook/script:
   jupyter notebook Titanic_Survival_Prediction.ipynb
4. Explore the data, run preprocessing, train the model, and evaluate predictions.
## Results
- Example: Logistic Regression achieved **~80% accuracy** on the test set (adjust based on your actual results).  
- Visualizations include survival distribution by `Sex`, `Pclass`, and `Age`.

## Future Improvements
- Test with more advanced models (Random Forest, XGBoost)  
- Perform hyperparameter tuning to optimize model performance  
- Feature engineering, e.g., combining `SibSp` and `Parch` into a **family size** feature  

## Author
- **Aziz Wei**  
- **Email:** [mohamedaziz.weili@supcom.ucar.tn]  
- **GitHub:** [https://github.com/<azizweili>](https://github.com/<azizweili>)


   
