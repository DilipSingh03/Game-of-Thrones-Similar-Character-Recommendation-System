# 🐉 Game of Thrones Similar Character Prediction

## 📌 Overview

The **Game of Thrones Similar Character Prediction** project is a Natural Language Processing (NLP) based recommendation system that identifies characters with similar traits, backgrounds, and descriptions from the *Game of Thrones* universe.

The project uses text preprocessing, TF-IDF vectorization, and Cosine Similarity to analyze character information and recommend the most similar characters based on a user's input.

---

## 🎯 Project Objective

Build an NLP-powered recommendation system capable of finding the most similar Game of Thrones characters using textual information such as:

* Character Description
* House
* Titles
* Culture
* Allegiance
* Personality Traits

---

## 🚀 Features

* Character similarity prediction
* NLP-based text preprocessing
* TF-IDF Vectorization
* Cosine Similarity Recommendation
* Fast and accurate recommendations
* Easy-to-use Python interface

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Pickle

---

## 📂 Project Structure

```text
Game_of_Thrones_Similar_Character_Prediction/

│── data/
│   └── characters.csv
│
│── notebooks/
│   └── GOT_Character_Recommendation.ipynb
│
│── models/
│   ├── tfidf_vectorizer.pkl
│   └── similarity_matrix.pkl
│
│── src/
│   ├── preprocessing.py
│   ├── recommender.py
│   └── utils.py
│
│── requirements.txt
│── README.md
```

---

## ⚙️ Workflow

1. Load the Game of Thrones character dataset.
2. Clean and preprocess the textual data.
3. Merge relevant text features into a single document.
4. Convert text into numerical vectors using TF-IDF.
5. Calculate pairwise cosine similarity between characters.
6. Recommend the top similar characters for the selected input.

---

## 🧠 Machine Learning Pipeline

```text
Character Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Text Preprocessing
        │
        ▼
Feature Engineering
        │
        ▼
TF-IDF Vectorization
        │
        ▼
Cosine Similarity
        │
        ▼
Top-N Similar Character Recommendation
```

---

## 📊 Example

**Input**

```text
Jon Snow
```

**Output**

```text
Robb Stark
Arya Stark
Ned Stark
Samwell Tarly
Jeor Mormont
```

---

## 💡 Skills Demonstrated

* Natural Language Processing (NLP)
* Text Preprocessing
* Feature Engineering
* TF-IDF Vectorization
* Cosine Similarity
* Recommendation Systems
* Data Analysis
* Python Programming

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Game_of_Thrones_Similar_Character_Prediction.git
```

Move to the project directory:

```bash
cd Game_of_Thrones_Similar_Character_Prediction
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## 📌 Future Improvements

* Integrate transformer-based sentence embeddings (e.g., Sentence-BERT).
* Add filtering by House, Region, or Status.
* Improve recommendations using hybrid similarity methods.
* Expand the dataset with additional character metadata.

---

## 👤 Author

**Dilip Singh Shaktawat**

* GitHub: https://github.com/DilipSingh03
* LinkedIn: https://www.linkedin.com/in/dilip-singh-77581b409

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
