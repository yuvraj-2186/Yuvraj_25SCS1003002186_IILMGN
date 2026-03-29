# AIML Project: Plagiarism Detector

This project is a **Plagiarism Detection System** developed using classical Natural Language Processing (NLP) techniques. It analyzes text documents and identifies similarity between them using mathematical representations of language.

---

## 🧠 Overview

The system converts textual data into numerical form and evaluates similarity between documents using:

- **TF-IDF (Term Frequency – Inverse Document Frequency)**
- **Cosine Similarity**

It provides a simple yet effective way to detect copied or similar content without relying on heavy deep learning models.

---

## 🎯 Objectives

- Build a functional plagiarism detection system
- Demonstrate NLP concepts like TF-IDF and cosine similarity
- Provide an interactive interface for document comparison
- Identify overlapping or suspicious content between files
- Create an educational tool to understand text similarity

---

## ⚙️ How It Works

The system follows a structured pipeline:

1. **Input Acquisition**  
   Users upload text documents through the interface

2. **Preprocessing**  
   - Convert text to lowercase  
   - Remove unnecessary spaces and symbols  
   - Clean formatting noise  

3. **Feature Extraction**  
   Convert text into vectors using TF-IDF

4. **Similarity Computation**  
   Use cosine similarity to measure closeness between documents

5. **Result Output**  
   - Similarity scores  
   - Suspicious document pairs  
   - Similarity matrix  

---

## 🛠️ Tech Stack

- **Python**
- **Scikit-learn**
- **Streamlit**
- **Natural Language Processing (NLP)**

---

## 📊 Features

- Detects exact and near-duplicate content  
- Identifies similarity between multiple documents  
- Displays similarity matrix for analysis  
- Interactive web interface using Streamlit  
- Fast and lightweight execution  

---

## 📈 Results

- Identical documents → similarity close to **1**
- Paraphrased content → moderately high similarity
- Unrelated documents → similarity close to **0**

---

## ⚠️ Limitations

- Cannot detect deep conceptual plagiarism  
- Depends on word overlap, not full semantic understanding  
- Works only with text files currently  

---

## 🚀 Future Scope

- Integration of advanced NLP models (embeddings)
- Support for PDF and DOCX files
- Highlighting copied sections
- Cross-language plagiarism detection
- Deployment as a scalable web application

---

## 📄 Project Report

📄 [View Full Project Report](Plagiarism%20Detector%20-%20Project%20Report.pdf)

---

## 🎯 Conclusion

This project demonstrates how classical NLP techniques can effectively detect similarity between documents. It serves both as a functional tool and as a foundational step towards more advanced AI-based text analysis systems.

---

## 👨‍💻 Author

**Yuvraj Singh**  
B.Tech CSE (Cyber Security)  
IILM University, Greater Noida
