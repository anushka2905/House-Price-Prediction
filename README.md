# House Price Prediction

A machine learning project to predict house prices using Linear Regression and Random Forest models.

## 🎯 Project Overview

This analysis builds regression models to predict house prices based on 11 property features including:
- Lot size
- Number of bedrooms & bathrooms
- Garage spaces
- Property amenities (AC, driveway, etc.)

## 📊 Models Trained

1. **Linear Regression**
   - R² Score: -0.0805
   - MAE: $80,382
   - RMSE: $92,365

2. **Random Forest Regressor**
   - R² Score: -0.0740
   - MAE: $79,080
   - RMSE: $92,087

## 🔝 Key Findings

- **Most influential features:**
  1. Lot Size (41% importance)
  2. Garage (10% importance)
  3. Bedrooms (9% importance)

- Property size (lot size) is the strongest price driver
- Accurate pricing requires additional data like location and market conditions

## 📈 Visualizations

- Price distribution histogram
- Feature correlation heatmap
- Actual vs Predicted scatter plots
- Feature importance chart

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation & analysis
- **Scikit-learn** - Machine learning models
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive analysis

## 📋 Project Structure

- `analysis.ipynb` - Complete Jupyter notebook with all analysis
- `data/Housing.csv` - Dataset used
- `charts/` - Generated visualizations
- `models/` - Trained model files

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/YOUR-USERNAME/house-price-prediction.git
cd house-price-prediction
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook analysis.ipynb
```

## 📚 What I Learned

- End-to-end ML pipeline (data loading → cleaning → modeling → evaluation)
- Model comparison & selection
- Feature importance analysis
- Data visualization techniques
- Handling categorical variables with one-hot encoding

## 🎓 Context

**XYlofy AI Internship - Week 1 Project**
- Completed: June 2026
- Skills: Python, ML, Data Analysis, Jupyter Notebooks

## 📧 Contact

For questions or feedback, reach out!

---

**Happy exploring!** 🎉
