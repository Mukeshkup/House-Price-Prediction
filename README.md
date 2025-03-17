# 🏠 Bengaluru House Price Prediction

## 📌 Overview
This project aims to predict house prices in Bengaluru using machine learning techniques.

## 📂 Project Structure
├── Bengaluru_House_Data.csv    # Raw dataset

├── cleaned_data.csv            # Preprocessed dataset

├── house_price.ipynb           # Jupyter Notebook for model training

├── RidgeModel.pkl              # Saved Ridge Regression Model

├── RidgeModelTuned.pkl         # Tuned Ridge Regression Model


## 🔍 Data Description
- **Bengaluru_House_Data.csv**: Raw dataset containing house prices and related features.
- **cleaned_data.csv**: Processed dataset after data cleaning and feature engineering.
- **house_price.ipynb**: Jupyter Notebook containing EDA, feature selection, model training, and evaluation.
- **RidgeModel.pkl**: Trained Ridge Regression model.
- **RidgeModelTuned.pkl**: Tuned Ridge Regression model with optimized hyperparameters.

## 🛠 Technologies Used
- Python 🐍
- Pandas, NumPy (Data Processing)
- Scikit-Learn (Machine Learning)
- Matplotlib, Seaborn (Data Visualization)

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Mukeshkup/house-price-prediction.git
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
3. Run the Jupyter Notebook to train the model or use the pre-trained models.

## 📈 Model Performance
- The Ridge Regression model was chosen due to its ability to handle multicollinearity.
- Performance metrics:
      - R² Score: Achieved a good fit on the test data.
      - Mean Absolute Error (MAE): Shows minimal error in price predictions.

## 🎯 Future Improvements
- Experiment with other ML algorithms (XGBoost, Random Forest, etc.)
- Deploy the model as a web application using Flask or Streamlit
- Add a user-friendly interface for predictions

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

⭐ If you like this project, consider giving it a star on GitHub!
