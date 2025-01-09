
# Municipal Solid Waste (MSW) Prediction: A Multi-Model Regression Analysis  

## 🌟 **Overview**  
This repository contains the complete codebase, models, and evaluation metrics used in the research paper titled **"Predicting Municipal Solid Waste (MSW) Generation Using Machine Learning Models"**. The project explores multiple regression techniques to forecast MSW generation based on socioeconomic and demographic factors.

## 📂 **Repository Structure**  
```plaintext
├── models/
│   ├── Linear_Regression.pkl  # Trained Linear Regression model
│   ├── Random_Forest.pkl      # Trained Random Forest model
│   ├── Gradient_Boosting.pkl  # Trained Gradient Boosting model
│   └── ...                    # Additional models
├── README.md                  # This file
└── requirements.txt           # Python dependencies
```

## 📊 **Key Results**  
The models were evaluated using four metrics: **Mean Squared Error (MSE)**, **R² Score**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.  

| Model                       | MSE          | R²     | MAE      | RMSE     |
|-----------------------------|--------------|--------|----------|----------|
| Linear Regression           | 241,858,412  | -0.986 | 6,755.59 | 15,551.80 |
| Ridge Regression            | 169,233,744  | -0.390 | 6,442.56 | 13,008.99 |
| ElasticNet Regression       | 63,673,562   | 0.477  | 6,228.82 | 7,979.57  |
| Random Forest Regressor     | 12,967,325   | 0.894  | 2,001.30 | 3,601.02  |
| Gradient Boosting Regressor | 17,871,457   | 0.853  | 2,307.52 | 4,227.46  |
| AdaBoost Regressor          | 25,771,039   | 0.788  | 3,012.38 | 5,076.52  |

**👉 Highlights**:  
- **Random Forest Regressor** outperformed other models with the highest R² score (0.894).  
- **Linear Regression** showed the weakest performance, indicating the need for non-linear models in MSW prediction.  

## 🔍 **How to Use**  

1. **Clone the Repository**  
   ```bash
   https://github.com/Kartikgarg74/Waste_Management.git
   cd Waste Management
   ```

2. **Explore Notebooks**  
   Open Jupyter Notebooks for detailed analysis:  
   ```bash
   jupyter notebook notebooks/WASTE MANAGEMENT PAPER.ipynb
   ```

## 🤝 **Contributions**  
Contributions, issues, and feature requests are welcome! Feel free to fork this repository and submit pull requests.  

## 🙌 **Acknowledgments**  
- **Dataset**: [https://www.greenpolicyplatform.org/initiatives/global-waste-management-outlook/Data](#)  
- **Libraries Used**: Scikit-learn, Plotly, Matplotlib, NumPy, Pandas  
