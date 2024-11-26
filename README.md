
# 🏠 House Price Prediction in Kota Bandung

This is a **machine learning-based web application** for predicting house prices in the city of Bandung, Indonesia. The app uses property characteristics as inputs and provides price predictions based on a trained LightGBM regression model.

---

## 🚀 Features

- **User-Friendly Interface**: Built with Streamlit for easy interaction.
- **District Classification**: Supports multiple districts in Kota Bandung, grouped into categories for better feature engineering.
- **Property Features Input**:
  - Land Area (LB)
  - Building Area (LT)
  - Number of Bedrooms (KT)
  - District selection with automatic categorization
- **Outlier Handling**: Employs custom logic to handle outliers in input data using IQR-based clipping.
- **Real-Time Price Prediction**: Predicts property prices instantly using a pre-trained LightGBM model.

---


## 🛠️ How to Run the Project

### Prerequisites
- Python 3.7 or later
- Required Python libraries:
  - `streamlit`
  - `pandas`
  - `numpy`
  - `sklearn`
  - `pickle`

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/house-price-prediction-bandung.git
   cd house-price-prediction-bandung
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run app.py
   ```
4. Open the application in your browser at `http://localhost:8501`.

---

## 🎯 Usage
1. Use the sidebar to input property features:
   - Land Area (LB)
   - Building Area (LT)
   - Number of Bedrooms (KT)
   - Choose the property district.
2. The app categorizes the district into predefined groups.
3. View the predicted house price on the main page.

---

## 🔧 Model Details
- **Model**: LightGBM Regressor
- **Outlier Handling**: Custom-built `HandlingOutliers` transformer.
- **Prediction Accuracy**: The model was trained and validated with high performance on Bandung housing data.

---

## 📈 Prediction Example

Input features:
- Land Area (LB): 150 m²
- Building Area (LT): 200 m²
- Bedrooms (KT): 3
- District: Coblong

**Predicted Price**: Rp 1,500,000,000



---

## 🤝 Contribution
Feel free to fork this repository, open issues, or submit pull requests for any improvements.

---

Would you like to include any additional sections or details? Let me know!
