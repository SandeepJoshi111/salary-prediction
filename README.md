# 💼 Salary Prediction

This project predicts developer salaries based on responses from the [Stack Overflow Developer Survey](https://survey.stackoverflow.co/). It utilizes machine learning models to provide insights based on user inputs like country, education, experience, and employment status.

---

## 📊 Dataset

- **Source**: [Stack Overflow Developer Survey](https://survey.stackoverflow.co/)
- The dataset is cleaned and preprocessed before training.


##Project Structure
```
.
├── app.py                 # Main Streamlit application
├── SalaryPrection.ipynb   # Data cleaning and training
├── saved_steps.pkl        # Trained machine learning model
├── explore_page.py        # Explore page display
├── predict_page.py        # Predict page display
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```
## 🚀 Features

- Predicts estimated annual salary
- Trained using real-world data
- Streamlit web interface
- Easy to use and extend

---

## 🛠️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/SandeepJoshi111/salary-prediction.git
cd salary-prediction
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

2. **Run the application**

```bash
streamlit run app.py
```


