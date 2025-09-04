# 📈 Bitcoin Price Prediction  

---

## 📌 1. Project Title  
**Bitcoin Price Prediction using Machine Learning**  

---

## ✅ 2. Objectives  
- Perform **exploratory data analysis (EDA)** on Bitcoin dataset.  
- Understand **correlations** among blockchain and market features.  
- Train and evaluate **machine learning models** (Linear Regression, Random Forest).  
- Visualize insights with **matplotlib & seaborn**.  
- Forecast Bitcoin’s market price using historical features.  

---

## 🛠 3. Tools & Technologies  
- **Programming Language**: Python  
- **Libraries Used**:  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
- **Files in this Repository**:  
  - [`Model/Bitcoin_Price_Prediction.ipynb`](./Model/Bitcoin_Price_Prediction.ipynb) – Jupyter Notebook with full workflow  
  - [`Dataset/bitcoin_dataset.csv`](./Dataset/bitcoin_dataset.csv) – Dataset used for analysis  
  - [`requirements.txt`](./requirements.txt) – Project dependencies  
  - [`Images/`](./Images) – Visualizations and plots from EDA  

---

## 🔍 4. Process  

### **Step 1: Data Collection**  
- Dataset used: [`bitcoin_dataset.csv`](./Dataset/bitcoin_dataset.csv)  
- Features include:  
  - Market Price  
  - Mining Difficulty  
  - Block Size  
  - Trade Volume  
  - Transaction Fees  
  - Miner Revenue  
  - Total Bitcoins  

---

### **Step 2: Installation**  
Clone the repository and install dependencies:  

```bash
git clone https://github.com/yourusername/Bitcoin_Price_Prediction.git
cd Bitcoin_Price_Prediction
pip install -r requirements.txt
```
---

### **Step 3: Data Preprocessing**  
- Handled **missing values** using median/mode imputation.  
- Converted **Date** column to datetime format for time-series analysis.  
- Applied **feature scaling (normalization)** to improve model performance.  

---

### **Step 4: Exploratory Data Analysis (EDA)**  
- Visualized **historical trends** for Bitcoin price and related features.  
- Created **correlation heatmap** to identify relationships among variables.  
- Generated **line plots, scatter plots, and distribution plots** for insights.  

📊 **Key Visualizations**:  
- Correlation Heatmap → `Images/image1.png`  
- Feature Trends → `Images/image2.png`  
- Scatter Plots → `Images/image4.png`  
- Difficulty vs Transactions → `Images/image5.png`  
- Total Bitcoins vs Price → `Images/image3.png`  

---

### **Step 5: Model Training & Evaluation**  
- Implemented **Linear Regression** as a baseline model.  
- Applied **Random Forest Regressor** for better prediction accuracy.  
- Evaluated models using:  
  - **R² Score**  
  - **Mean Squared Error (MSE)**  

✅ **Performance Comparison**:  
- **Linear Regression** → Lower accuracy, higher MSE.  
- **Random Forest** → Higher accuracy, better handling of non-linear patterns.  

---

## 🌟 6. Key Features  
- Complete **data cleaning and preprocessing pipeline**.  
- **Feature correlation analysis** using heatmaps and scatter plots.  
- **Two ML models** for regression-based Bitcoin price prediction.  
- Model evaluation with **R² Score** and **MSE** for performance assessment.  

---

## 🔍 7. Analysis Insights  
- **Strong correlation** found between Market Price and Mining Difficulty.  
- Weak correlation with **Block Size** and **Trade Volume**.  
- Time-series patterns show **price rises correlate with mining and network activity**.  

---

## ✅ 8. Outcomes  
- Built a **machine learning pipeline** for Bitcoin price prediction.  
- **Random Forest** significantly outperformed Linear Regression.  
- Discovered strong links between **Bitcoin price & blockchain fundamentals**.  
- Delivered **clear visualizations** for decision-making and analysis.  

---