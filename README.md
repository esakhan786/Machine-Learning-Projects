# 🚗 Car Price Predictor (Machine Learning Project)

## 📌 Overview

This project is a **Machine Learning model** that predicts the price of a car based on various features such as brand, year, fuel type, and more.
It includes **data cleaning, model training, and a web interface** for predictions.

---

## 🧠 Features

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Model training using Linear Regression
* Saved trained model (`LinearRegression.pkl`)
* Simple web app using Flask

---

## 📂 Project Structure

```
├── app.py                 # Flask application
├── LinearRegression.pkl  # Trained ML model
├── cleaned_data.csv      # Processed dataset
├── templates/            # HTML files
├── static/               # CSS/JS files
├── notebook.ipynb        # Jupyter notebook (EDA + training)
├── .gitignore
└── README.md
```

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Flask

---

## 🚀 How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Create virtual environment

```
python -m venv venv
```

### 3. Activate environment

* Windows:

```
venv\Scripts\activate
```

* Mac/Linux:

```
source venv/bin/activate
```

### 4. Install dependencies

```
pip install -r requirements.txt
```

### 5. Run the app

```
python app.py
```

---

## 📊 Model Used

* Linear Regression (from Scikit-learn)

---

## 📈 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Deploy the app online
* Improve UI/UX

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📜 License

This project is open-source and available under the MIT License.
