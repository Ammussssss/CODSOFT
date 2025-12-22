🎬 Movie Genre Classification using Machine Learning

This project focuses on predicting the genre of a movie based on its plot summary using Natural Language Processing (NLP) and Machine Learning techniques.

The project was developed as part of the CodSoft Machine Learning Internship.

📊 Dataset Information

Dataset: Movie Genre Classification Dataset (Kaggle)
⚠️ Dataset Note:
The original dataset file is large and exceeds GitHub’s file size limit.
Hence, it has not been uploaded to this repository.

Dataset Source:
https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb

You can download the dataset directly from Kaggle and place it in the project folder to run the notebook.

Input: Movie plot summaries

Target: Movie genre

Type: Multi-class text classification

Challenge: Multiple genres, class imbalance, overlapping genre themes

🧠 Model & Approach

Text Preprocessing:

Lowercasing

Removing punctuation and special characters

Text Vectorization:

TF-IDF Vectorizer (max features = 5000)

Machine Learning Model:

Logistic Regression (multi-class classification)

📈 Model Performance

Accuracy: ~58%

Performance varies across genres due to:

Overlapping genre themes

Fewer samples for rare genres

For multi-class genre classification, this accuracy is considered acceptable for a baseline NLP model.

🚀 Features

✔ Predicts movie genre from plot text
✔ Uses NLP and TF-IDF vectorization
✔ Handles multi-class classification
✔ Saves trained model and vectorizer
✔ Simple and extendable pipeline

📁 Project Structure
Task1_Movie_Genre_Classification/
│
├── Movie_Genre_Classification.ipynb
├── train_data.txt
├── README.md
│
├── models/
│   ├── genre_model.pkl
│   └── tfidf_vectorizer.pkl
│
└── results/

👩‍💻 Author

Amrutha
Machine Learning Intern — CodSoft

⭐ Acknowledgment

Thanks to CodSoft for providing the opportunity to work on NLP-based machine learning projects.