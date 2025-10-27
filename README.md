# 🧠 Resume Matcher using Flask

This project is a **Resume Matcher Web App** built using **Flask** and **Machine Learning (TF-IDF + Cosine Similarity)**.  
It helps **HRs and recruiters** automatically find the **top 3 resumes** that best match a given **Job Description**, saving hours of manual screening.

---

## 🚀 Features

✅ Upload multiple resumes (PDF, DOCX, TXT formats)  
✅ Enter a Job Description directly in the app  
✅ Automatically extracts text from resumes  
✅ Computes similarity using **TF-IDF vectorization** and **Cosine Similarity**  
✅ Displays **Top 3 matching resumes** with their similarity scores  
✅ User-friendly Bootstrap interface  

---

## 🧩 Tech Stack

| Component | Technology Used |
|------------|----------------|
| Backend | Flask (Python) |
| Frontend | HTML, CSS, Bootstrap |
| NLP / ML | Scikit-learn (TF-IDF Vectorizer, Cosine Similarity) |
| File Handling | PyPDF2, docx2txt, OS |
| Language | Python 3.x |


## 🏗️ Project Structure
ResumeMatcher/
│
├── app.py # Main Flask Application
├── templates/
│ └── matchresume.html # Frontend HTML file
├── uploads/ # Folder where uploaded resumes are stored
├── requirements.txt # All dependencies
└── README.md # Project documentation
