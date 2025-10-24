
***

# Healthcare Premium Prediction

This project is a **machine learning-based regression application** that predicts insurance premium costs based on user-provided demographic and health-related information. It provides an **interactive web interface** using **Streamlit** for real-time predictions and visualization.

***

## Features

- Predicts insurance premiums using regression models.  
- Interactive user interface built with Streamlit.  
- Real-time input and prediction display.  
- Includes feature engineering and model evaluation (RMSE, MAE, R²).  

***

## Tech Stack

- **Python**  
- **scikit-learn**  
- **NumPy**  
- **Pandas**  
- **Streamlit**

***

## Project Structure

```
Healthcare-Premium-Prediction/
│
├── app/
│   └── main.py              # Streamlit application entry point
│
├── model/
│   ├── model.pkl            # Trained regression model (if available)
│   └── scaler.pkl           # Data scaler used during preprocessing
│
├── data/
│   └── dataset.csv          # Dataset used for training (optional)
│
├── requirements.txt         # List of dependencies
├── README.md
└── ...
```

***

## Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/ABHI9234/Healthcare-Premium-Prediction.git
   cd Healthcare-Premium-Prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app locally:

   ```bash
   streamlit run app/main.py
   ```

4. The app will open in your default browser, usually at:

   ```
   http://localhost:8501
   ```

***

## Model Details

The prediction model uses regression algorithms to estimate healthcare insurance premiums. Key steps:

- Data preprocessing  
- Feature engineering  
- Model training and evaluation  
- Deployment via Streamlit interface  

***

## Output Example

Users can input parameters such as **age**, **BMI**, **smoking status**, and **region**, then receive a **predicted premium** instantly through the web interface.

***


***

