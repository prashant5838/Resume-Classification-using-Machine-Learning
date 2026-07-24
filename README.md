# Resume-Classification-using-Machine-Learning

## Overview

This project classifies resumes into predefined job categories using Natural Language Processing (NLP) and Machine Learning algorithms.

The model is trained on a resume dataset and predicts the most suitable category for a given resume based on its textual content.

---

## Features

- Resume text preprocessing
- Text cleaning
- TF-IDF Vectorization
- Machine Learning classification
- Resume category prediction
- Model evaluation

---

## Dataset

The project uses `resume_dataset.csv`.

Each record contains:

- Resume Text
- Resume Category

Example Categories:

- Data Science
- Java Developer
- Python Developer
- HR
- Testing
- DevOps
- Business Analyst
- Mechanical Engineer

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- NLTK

---

## Machine Learning Models

- Multinomial Naive Bayes
- K-Nearest Neighbors
- OneVsRest Classifier

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Resume-Screening.git

cd Resume-Screening
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Resume_Screening.ipynb
```

Run all cells.

---

## Workflow

1. Load Dataset
2. Clean Resume Text
3. Extract Features using TF-IDF
4. Train Machine Learning Model
5. Predict Resume Category
6. Evaluate Model Performance

---

## Project Structure

```
Resume-Screening/
│
├── Resume_Screening.ipynb
├── resume_dataset.csv
├── Cover.png
└── README.md
```

---

## Future Improvements

- Deep Learning models
- BERT embeddings
- Resume parsing from PDF
- Streamlit interface
- Job Description matching
- Candidate ranking

---

## Author

Prashant Gurematti
