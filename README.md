# students-marks-predictor

# 🎓 Students Marks Predictor

A Machine Learning web application built using **Python**, **Flask**, and **Scikit-learn** to predict students' marks based on their academic information. The trained model is integrated into a Flask web application, allowing users to enter input values and receive predicted marks instantly.

---

## 📌 Features

- Predict student marks using a trained Machine Learning model.
- User-friendly web interface built with Flask.
- Real-time predictions.
- Simple and responsive design.
- Easy to run locally.

---

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- HTML
- CSS
- Jupyter Notebook

---

## 📂 Project Structure

```
Students-Marks-Predictor/
│
├── static/
├── templates/
├── Desktop.pkl
├── Students-Marks_Predictor.ipynb
├── app.py
├── flaskpractise.py
├── smp_data_from_app.csv
├── student_info.csv
└── README.md
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/students-marks-predictor.git
```

### 2. Navigate to the project folder

```bash
cd students-marks-predictor
```

### 3. Install the required packages

```bash
pip install -r requirements.txt
```

### 4. Run the Flask application

```bash
python app.py
```

### 5. Open your browser

```
http://127.0.0.1:5000/
```

---

## 📊 Dataset

The project uses:

- `student_info.csv`
- `smp_data_from_app.csv`

These datasets are used for training and storing prediction data.

---

## 🤖 Machine Learning Model

The trained model is saved as:

```
Desktop.pkl
```

It is loaded inside the Flask application to generate predictions.

---

## 📸 Application Workflow

1. User enters student information.
2. Flask receives the input.
3. The trained ML model processes the data.
4. Predicted marks are displayed on the webpage.

---

## 📦 Requirements

- Python 3.x
- Flask
- NumPy
- Pandas
- Scikit-learn
- Joblib

---

## 📈 Future Improvements

- Improve prediction accuracy.
- Deploy the application on Render or Heroku.
- Add user authentication.
- Store prediction history in a database.
- Enhance the UI with Bootstrap.

---

## 👩‍💻 Author

**Ankita Shendge**

GitHub: https://github.com/shendgeankita522-blip

---

## ⭐ If you found this project useful, don't forget to give it a star!
