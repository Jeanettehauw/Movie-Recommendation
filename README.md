# 🎬 Movie Recommendation System

A machine learning project that builds a **Movie Recommendation System** using **Multinomial Naïve Bayes**, **TF-IDF Vectorizer**, and **Cosine Similarity**.

---

## 📌 Features
- **Review Classification**: Classifies user reviews (positive/negative) with **MultinomialNB**.  
- **Content-Based Recommendations**: Suggests similar movies using **TF-IDF + Cosine Similarity**.  
- **Named Entity Recognition (NER)**: Extracts movie titles, actors, and directors from reviews.  
- **Interactive Search**: Input a movie or keyword and get personalized recommendations.  

---

## 🛠️ Tech Stack
- **Python**  
- **Scikit-learn** (MultinomialNB, TF-IDF, Cosine Similarity)  
- **Pandas & NumPy** (data preprocessing)  
- **NLTK / SpaCy** (text preprocessing & NER)  

---

## 📊 Dataset
- IMDb dataset with movie reviews, and ratings.  

---

## 🚀 How It Works
1. **Data Preprocessing**: Clean text, remove stopwords, and lemmatize.  
2. **Vectorization**: Transform reviews into **TF-IDF vectors**.  
3. **Classification**: Train a **Multinomial Naïve Bayes** model for sentiment analysis.  
4. **Recommendation**: Use **Cosine Similarity** to find and recommend similar movies.  

---

## ▶️ Usage
```bash
# Clone the repository
git clone https://github.com/your-username/movie-recommendation-nb.git

# Navigate to project folder
cd movie-recommendation-nb

# Install dependencies
pip install -r requirements.txt

# Run the system
python main.py
