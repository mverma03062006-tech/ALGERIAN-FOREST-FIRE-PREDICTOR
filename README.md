# 🔥 Algerian Forest Fire Prediction

A Machine Learning-based web application that predicts the **Fire Weather Index (FWI)** using the Algerian Forest Fires Dataset. The project covers the complete Machine Learning workflow, from Exploratory Data Analysis and Feature Engineering to Model Training and Flask-based Deployment.

## 🌐 Live Demo

🚀 **[Try the Live Application](https://algerian-forest-fire-prediction-33yc.onrender.com)**

## 📌 Project Overview

Forest fires are a major environmental concern, causing significant damage to ecosystems and biodiversity.

This project uses Machine Learning to predict the **Fire Weather Index (FWI)** based on meteorological and environmental conditions.

A **Ridge Regression** model is trained on the Algerian Forest Fires Dataset, with StandardScaler used for feature scaling. The trained model is integrated into a Flask web application to provide real-time predictions through a user-friendly interface.

## 🚀 Features

- 🔥 Predicts Fire Weather Index (FWI).
- 🤖 Machine Learning model using Ridge Regression.
- 📊 Exploratory Data Analysis (EDA).
- ⚙️ Feature Engineering and Data Preprocessing.
- 📏 Feature Scaling using StandardScaler.
- 🌐 Interactive Flask-based web interface.
- 💾 Model serialization using Pickle.
- ☁️ Live deployment using Render.

## 📊 Dataset

The project uses the **Algerian Forest Fires Dataset**, which contains meteorological observations and fire-related information collected from two regions of Algeria.

### Input Features

| Feature | Description |
|---|---|
| Temperature | Temperature in Celsius |
| RH | Relative Humidity (%) |
| Ws | Wind Speed (km/h) |
| Rain | Rainfall (mm) |
| FFMC | Fine Fuel Moisture Code |
| DMC | Duff Moisture Code |
| ISI | Initial Spread Index |
| Classes | Fire / Not Fire classification |
| Region | Geographic region |

### Prediction Output

**Fire Weather Index (FWI)** – An indicator used to estimate the potential intensity of forest fires.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Flask | Web Application Framework |
| Scikit-learn | Machine Learning |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib & Seaborn | Data Visualization |
| Pickle | Model Serialization |
| HTML & CSS | Frontend Development |
| Render | Cloud Deployment |
| Jupyter Notebook | Model Development |

## 📂 Project Structure

```text
ALGERIAN-FOREST-FIRE-PREDICTOR/
│
├── models/
│   ├── ridge.pkl
│   ├── scaler.pkl
│   └── Algerian_forest_fires_dataset_UPDATE.csv
│
├── notebooks/
│   ├── 2.0-EDA And FE Algerian Forest Fires.ipynb
│   └── 3.0-Model Training.ipynb
│
├── templates/
│   ├── home.html
│   └── index.html
│
├── application.py
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/mverma03062006-tech/ALGERIAN-FOREST-FIRE-PREDICTOR.git
```

### 2. Navigate to the Project Directory

```bash
cd ALGERIAN-FOREST-FIRE-PREDICTOR
```

### 3. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it:

**Windows:**
```bash
venv\Scripts\activate
```

**Linux / macOS:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Flask Application

```bash
python application.py
```

### 6. Open in Browser

Visit:

```text
http://127.0.0.1:5000
```

## 🤖 Machine Learning Model

The project uses **Ridge Regression**, a regularized linear regression algorithm.

### Model Workflow

1. Load and understand the Algerian Forest Fires Dataset.
2. Perform Exploratory Data Analysis.
3. Clean and preprocess the dataset.
4. Perform Feature Engineering.
5. Split the dataset into training and testing sets.
6. Apply StandardScaler for feature scaling.
7. Train the Ridge Regression model.
8. Serialize the trained model and scaler using Pickle.
9. Integrate the model into the Flask application.
10. Generate predictions through the web interface.

### Model Components

- **Algorithm:** Ridge Regression
- **Regularization:** L2 Regularization
- **Feature Scaling:** StandardScaler
- **Model Storage:** Pickle

## 📸 Application Preview

Explore the deployed application:

👉 [Algerian Forest Fire Prediction – Live Demo](https://algerian-forest-fire-prediction-33yc.onrender.com)

*Add screenshots of the application interface here.*

## 🔮 Future Improvements

- Improve the frontend with Bootstrap.
- Display model evaluation metrics.
- Add input validation and error handling.
- Compare multiple regression algorithms.
- Improve prediction accuracy through hyperparameter tuning.
- Enhance the user experience and application responsiveness.

## 👨‍💻 Author

**Mayur**

- GitHub: [@mverma03062006-tech](https://github.com/mverma03062006-tech)
- Project Repository: [ALGERIAN-FOREST-FIRE-PREDICTOR](https://github.com/mverma03062006-tech/ALGERIAN-FOREST-FIRE-PREDICTOR)

---

⭐ If you find this project interesting, consider giving the repository a star!

**Built with Python, Machine Learning and Flask.**
