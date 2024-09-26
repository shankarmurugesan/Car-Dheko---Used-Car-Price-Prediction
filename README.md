**Predicting Car Prices with Machine Learning Models**

## **Overview**
This project predicts used car prices based on features like make, model, year, fuel type, transmission, and more. Using CarDekho data, the aim is to build a user-friendly tool for both customers and sales reps. The final product is a deployed Streamlit app for instant price predictions.

## **Project Structure**
- **Jupyter Notebook**  
  *File*: `CarDheko_DataHandling_ModelBuild.ipynb`  
  *Description*: Contains data cleaning, feature engineering, model training, and evaluation.

- **Streamlit Application**  
  *File*: `CarDekho.py`  
  *Description*: Interactive app where users input car details for price predictions.

- **Project Report**  
  *File*: `Proj_Det.pdf`  
  *Description*: Detailed report covering the entire project lifecycle.

- **User Guide**  
  *File*: `GuideForUsers.pdf`  
  *Description*: Step-by-step guide on using the Streamlit app.

- **Resources**  
  *File*: `Resource_Files.zip`  
  *Contents*: Includes dataset, joblib files, and other resources.

## **Getting Started**
### Prerequisites
- Python 3.7+
- Required libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `streamlit`

### Streamlit Application Features
- **Input Fields**: Input attributes like make, model, year, fuel type, mileage, etc.
- **Price Prediction**: Click ‘Predict Value’ to get the car's estimated price.
- **User-Friendly Interface**: Accessible to both technical and non-technical users.

## **Model Training and Evaluation**
- **Data Cleaning**: Handled missing values, encoded categorical features, and scaled numerical ones.
- **Model Selection**: Tested various models (Linear Regression, Decision Trees, Random Forest, Gradient Boosting) with hyperparameter tuning.
- **Evaluation**: Evaluated using MSE, MAE, and R². Best-performing model selected for deployment.

## **Results**
- **Best Model**: Highest R² and lowest MSE/MAE chosen.
- **Accuracy**: High predictive accuracy, making it reliable for estimating car prices.

## **Repository Structure**
- `CarDheko_DataHandling_ModelBuild.ipynb`: Data processing and model training notebook.
- `CarDekho.py`: Streamlit app script.
- `Proj_Det.pdf`: Comprehensive project report.
- `GuideForUsers.pdf`: User guide for the app.
- `Resource_Files.zip`: Dataset, joblib files, and resources.

- ## **Sample Screen shot**

- ![image](https://github.com/user-attachments/assets/46569439-f6f8-4416-be39-8a4bb9702c7c)

- ![image](https://github.com/user-attachments/assets/09c75dcf-8766-4a03-912d-b9ce0bafa22b)

