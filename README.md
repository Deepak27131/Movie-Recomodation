# 🎬 Movie Recommendation System  
### NLP + Machine Learning + FastAPI + Streamlit

<img width="1796" height="955" alt="image" src="https://github.com/user-attachments/assets/9dacdfba-912c-4c5b-b55b-eac6281a60f9" />

---

## 📌 Project Overview

This project is a full-stack Movie Recommendation System built using Natural Language Processing (NLP) and Machine Learning techniques.

The system recommends movies based on textual similarity of movie overviews using TF-IDF vectorization and Cosine Similarity.

It consists of:

- 🔹 FastAPI backend for recommendation logic
- 🔹 Streamlit frontend for interactive UI
- 🔹 Scikit-learn powered ML engine
- 🔹 NLP-based content filtering

---

## 🚀 Live Demo

🌐 Live Application:  
https://movie-recomodation.onrender.com

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Natural Language Processing (TF-IDF)  
- FastAPI  
- Streamlit  

---

## 🧠 How the Recommendation System Works

1. Movie overview text is cleaned and preprocessed.
2. Text is converted into numerical vectors using TF-IDF Vectorization.
3. Cosine Similarity is computed between all movies.
4. Based on user selection, the most similar movies are recommended.

This approach is called **Content-Based Filtering**.

---

## 📂 Project Structure

Movie-Recomodation/
│
├── app.py              # Streamlit frontend
├── main.py             # FastAPI backend
├── model.pkl           # Trained similarity matrix/model
├── movies.csv          # Dataset
├── requirements.txt    # Dependencies
└── README.md           # Documentation

---

## ⚙️ Installation & Setup Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Deepak27131/Movie-Recomodation.git
cd Movie-Recomodation
```

---

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3️⃣ Run FastAPI Backend

```bash
uvicorn main:app --reload
```

Backend runs at:
http://127.0.0.1:8000

---

### 4️⃣ Run Streamlit Frontend

```bash
streamlit run app.py
```

The application will open in your browser automatically.

---

## ✨ Key Features

✔ Content-Based Movie Recommendation  
✔ NLP-powered similarity matching  
✔ FastAPI REST API integration  
✔ Interactive Streamlit UI  
✔ Real-world ML deployment structure  

---

## 📊 Example Workflow

User selects a movie →  
System processes overview text →  
Calculates similarity scores →  
Returns Top N recommended movies.

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

- Natural Language Processing
- TF-IDF Vectorization
- Cosine Similarity
- API development using FastAPI
- UI development using Streamlit
- ML deployment and integration

---

## 🔮 Future Enhancements

- Add Collaborative Filtering
- Implement User Authentication
- Improve Recommendation Accuracy
- Add Docker Support
- Deploy using CI/CD pipeline
- Add movie posters and trailers API integration

---

## 🤝 Contribution

Contributions are welcome.

If you'd like to improve this project:
1. Fork the repository
2. Create a new branch
3. Submit a Pull Request

---

## 📬 Connect With Me

If you have feedback, suggestions, or collaboration ideas, feel free to connect with me.

---

⭐ If you found this project useful, please consider giving it a star!
