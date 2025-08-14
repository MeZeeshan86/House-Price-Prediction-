# 🏡 California Housing Price Prediction App

Streamlit web app predicting California housing prices using a trained **Random Forest** model.  
Features interactive inputs, auto-detection of ocean proximity, and an integrated heatmap for price visualization.  
Built with **Pandas**, **Folium**, and **Scikit-learn**, leveraging feature engineering and model optimization.

---

## 🚀 Features
- **Interactive inputs** for housing details
- **Automatic ocean proximity detection** via geodesic distance
- **Real-time house price prediction**
- **Folium map with heatmap and legend**
- **Optimized ML model** using GridSearchCV
- Built with **Pandas, Scikit-learn, Folium, Streamlit**

---

## 📂 Project Structure
```plaintext
.
├── app.py               # Streamlit web app
├── houseprice.py        # Model training & evaluation script
├── Dataset/
│   └── housing.csv      # California housing dataset
├── Pickle Model/
│   └── House_price.pkl  # Trained Random Forest model
└── README.md            # Project documentation
```

## 📊 Model Details

- **Algorithm**: Random Forest Regressor  
- **Feature Engineering**:
  - Bedroom-to-room ratio  
  - Rooms per household  
  - Log transformations for skewed features  
- **Optimization**: GridSearchCV  
- **Metrics**:
  - RMSE (Root Mean Squared Error)  
  - R² Score
## 🛠 Installation & Usage

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/california-housing-prediction.git
cd california-housing-prediction
```
### 2️⃣ Install all dependencies
```bash
pip install streamlit pandas numpy folium geopy scikit-learn matplotlib seaborn streamlit-folium
```
 ## 3️⃣ Run the Streamlit app
```bash
streamlit run app.py
```
## 🌟 Future Improvements
- Confidence intervals for predictions  
- Batch predictions via CSV upload  
- Map filters & clustering  

---

## 👨‍💻 Author
## **Zeeshan**  
Developed as a **data science & ML** learning project.

