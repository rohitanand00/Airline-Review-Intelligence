# Airline Review Intelligence: A Sentiment Analysis Approach ✈️

An end-to-end NLP and ML pipeline that analyzes 127K+ airline reviews to uncover key service drivers influencing customer satisfaction.

---

## 🚀 Project Overview
This project performs large-scale sentiment analysis on passenger reviews scraped from [AirlineQuality.com](https://www.airlinequality.com/).  
It combines **dual sentiment validation** (TextBlob + VADER), **ML classification**, and **prescriptive analytics** through dominance analysis.

---

## 🧠 Key Features
- **Data Volume:** 127,000+ reviews from 110+ airlines  
- **Dual Sentiment Validation:** TextBlob + VADER (72.94% label agreement)  
- **Modeling:** Logistic Regression (92.37% accuracy), BERT, DistilBERT  
- **Feature Insights:** Dominance analysis identified top satisfaction drivers  
  - Value for Money  
  - Ground Service  
  - Seat Comfort  
- **Automation:** End-to-end Python pipeline for preprocessing → labeling → modeling → visualization  

---

## 🛠️ Tech Stack
Python | Pandas | NumPy | Scikit-learn | SpaCy | TextBlob | VADER | HuggingFace Transformers | Dominance-Analysis | Matplotlib | Seaborn | WordCloud

---

## 📊 Methodology
Follows the **CRISP-ML(Q)** framework:
1. **Data Acquisition:** Web-scraping 127K+ reviews  
2. **Data Cleaning:** Emoji demojizing, stopword removal, chatword expansion  
3. **Sentiment Labeling:** Agreement-based dual validation  
4. **Modeling:** TF-IDF vectorization + Logistic Regression  
5. **Prescriptive Analytics:** Dominance analysis for feature ranking  
6. **Pipeline:** Automated Python workflow for reusability

---

## 📈 Model Performance
| Model | Accuracy |
|--------|-----------|
| Logistic Regression | **92.37%** |
| BERT | 88.00% |
| DistilBERT | 90.08% |

---

## 📌 Results
- Sentiment pipeline achieves **>92% accuracy** with interpretable coefficients.
- Dominance analysis provides actionable insights for airline managers.
- Framework adaptable for hospitality, healthcare, and retail feedback analytics.

---

## 📚 Author
**Rohit Anand**  
MBA – Business Analytics | University of Hyderabad  
[LinkedIn](https://linkedin.com/in/rohit-anand) | [Email](mailto:your.email@example.com)

---

## 🧩 Future Work
- Aspect-based sentiment analysis (ABSA)  
- Real-time review streaming via APIs  
- Streamlit dashboard integration  
- Multilingual sentiment detection
