# Gold Price Prediction

##  Overview
This project predicts gold prices using **Machine Learning** with a **Random Forest Regressor**.  
It leverages historical gold market data to forecast prices, enabling better insights for investors, traders, and analysts.

##  Dataset
- **Source**: Kaggle (included as `gld_price_data.csv` in the repository)
- **Features**:  
  - `Date` (if applicable)  
  - `SPX` – S&P 500 Index  
  - `USO` – Oil prices  
  - `SLV` – Silver prices  
  - `EUR/USD` – Euro to USD exchange rate  
  - `GLD` – Gold ETF closing price (target variable)
- **Target Variable**: `GLD` (Gold Price)

##  Methodology
1. **Data Collection & Preprocessing**
   - Loaded data from CSV file
   - Checked for missing values
   - Performed exploratory data analysis (EDA) with Seaborn & Matplotlib
   - Selected relevant features
2. **Model Training**
   - Model: **Random Forest Regressor**
   - Split data into **80% training** and **20% testing**
3. **Model Evaluation**
   - **R² Score**: `0.9901`
   - The model shows strong predictive capability

##  Results
- **R² Score**: **0.9901**  
- High accuracy indicates the model captures gold price trends effectively

## Technologies Used

Programming Language: Python

Libraries:Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Author
Ena Luhadia


```bash
git clone https://github.com/<your-username>/GoldPricePrediction.git
cd GoldPricePrediction
