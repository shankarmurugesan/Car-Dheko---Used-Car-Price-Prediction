**Predicting Car Prices with Machine Learning Models**

## **Overview**
This project predicts used car prices based on features like make, model, year, fuel type, transmission, and more. Using CarDekho data, the aim is to build a user-friendly tool for both customers and sales reps. The final product is a deployed Streamlit app for instant price predictions.

## **Project Structure**
- **Jupyter Notebook**  
  *File*: `car_dekho_cleaning_and_modeling.ipynb`  
  *Description*: Contains data cleaning, feature engineering, model training, and evaluation.

- **Streamlit Application**  
  *File*: `car_dekho_app.py`  
  *Description*: Interactive app where users input car details for price predictions.

- **Project Report**  
  *File*: `project_report.pdf`  
  *Description*: Detailed report covering the entire project lifecycle.

- **User Guide**  
  *File*: `user_guide.pdf`  
  *Description*: Step-by-step guide on using the Streamlit app.

- **Resources**  
  *File*: `resources.zip`  
  *Contents*: Includes dataset, joblib files, and other resources.

## **Getting Started**
### Prerequisites
- Python 3.7+
- Required libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `streamlit`

### Streamlit Application Features
- **Input Fields**: Input attributes like make, model, year, fuel type, mileage, etc.
- **Price Prediction**: Click ‘Predict’ to get the car's estimated price.
- **User-Friendly Interface**: Accessible to both technical and non-technical users.

## **Model Training and Evaluation**
- **Data Cleaning**: Handled missing values, encoded categorical features, and scaled numerical ones.
- **Model Selection**: Tested various models (Linear Regression, Decision Trees, Random Forest, Gradient Boosting) with hyperparameter tuning.
- **Evaluation**: Evaluated using MSE, MAE, and R². Best-performing model selected for deployment.

## **Results**
- **Best Model**: Highest R² and lowest MSE/MAE chosen.
- **Accuracy**: High predictive accuracy, making it reliable for estimating car prices.

## **Repository Structure**
- `car_dekho_cleaning_and_modeling.ipynb`: Data processing and model training notebook.
- `car_dekho_app.py`: Streamlit app script.
- `project_report.pdf`: Comprehensive project report.
- `user_guide.pdf`: User guide for the app.
- `Car_Price_Prediction.zip`: Dataset, joblib files, and resources.

## **Acknowledgements**
Data from CarDekho. Built with open-source libraries, including Scikit-learn and Streamlit.

## **License**
This project is licensed under the MIT License.
