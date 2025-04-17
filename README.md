
# 🧠 Multilingual Chatbot – Logic Only

This chatbot responds to user queries in Nepali, Romanized Nepali, or English using TF-IDF and cosine similarity.

## 🔧 How It Works (Logic Only)

**Combine Questions**
   - Merge Nepali, Romanized, and English versions of each question into one string for processing.

**Normalize Input**
   - Clean user queries using Unicode normalization, lowercasing, and space removal.

**TF-IDF Vectorization**
   - Convert all combined questions into TF-IDF vectors.

 **Find Best Match**
   - Transform the user query into a TF-IDF vector.
   - Use cosine similarity to compare it with stored questions.

 **Return Answer**
   - If similarity is above a threshold, return the matched answer.
   - Otherwise, return a fallback response.

 **Optional Image**
   - If an answer has an image path, display the image.


This repo shows the logic only — no sample data or UI code.
