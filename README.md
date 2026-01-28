# News Category Predictor 📰

A Machine Learning–based Natural Language Processing (NLP) project that classifies news articles into multiple categories such as Business, Sports, Technology, Politics, etc.

This project demonstrates an end-to-end NLP pipeline, from raw text preprocessing to category prediction, and includes an interactive user interface built using Gradio.

---
## 📌 Project Overview

With the rapid growth of online news, automatic categorization of news articles has become an important real-world problem.  
This project focuses on building a machine learning model that can accurately predict the category of a news article based on its textual content.

The model was developed and tested using **Google Colab** and provides an interactive **Gradio interface** for real-time predictions.

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Natural Language Processing (NLP)  
- Gradio  
- Google Colab  

---

## 🧠 Machine Learning Approach

1. **Data Preprocessing**
   - Text cleaning
   - Removal of unnecessary characters
   - Tokenization and normalization

2. **Feature Extraction**
   - TF-IDF (Term Frequency–Inverse Document Frequency) Vectorization

3. **Model Training**
   - Multi-class classification using a Machine Learning algorithm

4. **Prediction**
   - Predicts the most suitable news category for a given input text

---

## 🖥️ User Interface

An interactive interface is created using **Gradio**, allowing users to:
- Enter a news article or headline
- Instantly receive the predicted news category

---

## ▶️ How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/News-Category-Predictor.git
2.Navigate to the project directory:
   cd News-Category-Predictor
3.Install the required dependencies:
   pip install -r requirements.txt
4.Open the Jupyter Notebook:
  news_category_predictor.ipynb
5.Run all cells in the notebook.
6.The Gradio interface will launch for interactive predictions.
