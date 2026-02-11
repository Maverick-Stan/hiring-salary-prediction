# Hiring Salary Prediction (Beginner Machine Learning Project)

This project builds a simple **Linear Regression** model to predict candidate salaries based on three factors:

- Years of experience
- Written test score
- Interview score

The model is trained using a small hiring dataset and used to predict salaries for new candidates.

---

## Project Structure

```
hiring-salary-prediction/
│
├── data/
│   └── hiring.csv
│
├── hiring_salary_prediction.ipynb
├── requirements.txt
└── README.md
```

---

## Dataset

The dataset contains hiring statistics such as:

- `experience` – years of experience (originally in text form)
- `test_score` – written test score
- `interview_score` – interview performance score
- `salary` – salary offered to the candidate

---

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## How the Model Works

1. Load the hiring dataset.
2. Convert experience values from text (e.g., "five", "ten") into numbers.
3. Handle missing values.
4. Train a **Linear Regression** model.
5. Use the model to predict salaries for new candidates.

---

## How to Run the Project

### 1. Clone the repository

git clone https://github.com/Maverick-Stan/hiring-salary-prediction.git

### 2. Navigate into the project folder

cd hiring-salary-prediction

### 3. Install required libraries

pip install -r requirements.txt

### 4. Open the notebook

jupyter notebook

Then open:

hiring_salary_prediction.ipynb

Run all cells to see the predictions.

---

## Assignment Predictions

The model predicts salaries for the following candidates:

| Experience | Test Score | Interview Score |
|-----------|-----------|----------------|
| 2 years   | 9         | 6              |
| 12 years  | 10        | 10             |

The predicted salaries are displayed in the notebook output.

---

## Author

Women Techsters Fellowship – Machine Learning Assignment  
Class of 2026

