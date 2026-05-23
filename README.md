# AI Resume Screener

An AI-based Resume Screening System built using Machine Learning and NLP techniques.

## Project Overview

This project automatically screens resumes and matches them with a job description using Natural Language Processing (NLP) and Machine Learning.

The system:
- Extracts text from resumes
- Cleans and processes resume data
- Converts text into vectors using TF-IDF
- Calculates similarity scores
- Ranks resumes based on job relevance

---

# Features

- PDF Resume Reading
- DOCX Resume Reading
- TXT Resume Reading
- NLP Text Cleaning
- TF-IDF Vectorization
- Cosine Similarity Matching
- Resume Ranking System
- CSV Result Export

---

# Technologies Used

- Python
- Google Colab
- Scikit-learn
- Pandas
- NLTK
- PyPDF2
- pdfplumber

---

# Machine Learning Concepts Used

- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Cosine Similarity
- Text Classification

---

# Project Structure

```bash
AI-RESUME-SCREENER1/
│
├── AI_Resume_Screener.ipynb
├── requirements.txt
├── README.md
│
├── sample_resumes/
│   ├── resume1_data_science.pdf
│   ├── resume2_web_developer.pdf
│   ├── resume3_java_developer.pdf
│   └── resume4_android_developer.pdf
│
└── results/
    └── resume_screening_results.csv
```

---



# Example Output

| Resume Name | Match Score |
|-------------|-------------|
| resume1.pdf | 92.45% |
| resume2.pdf | 71.20% |
| resume3.pdf | 54.11% |

---



# Author

Abdul Hafiz

---

