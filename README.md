# Airline Review Intelligence: A Sentiment Analysis Approach ✈️

An end-to-end NLP and ML pipeline that **scrapes, processes, and analyzes 127K+ airline reviews** to uncover key service drivers influencing customer satisfaction.

---

## 🚀 Project Overview
This project performs large-scale sentiment analysis on passenger reviews **scraped programmatically from [AirlineQuality.com](https://www.airlinequality.com/)** using Python.  
From **data extraction to automated model deployment**, every step was built **from scratch** to create a reusable analytics framework.  
It integrates **dual sentiment validation** (TextBlob + VADER), **machine learning classification**, and **prescriptive analytics** through dominance analysis.

---

## 🧠 Key Features
- **Web Scraping:** Automated data extraction pipeline built with *BeautifulSoup*, *Requests*, and *Pandas* to collect 127,000+ reviews from 110+ airlines.  
- **Data Volume:** 127K+ reviews with 17 structured and unstructured variables.  
- **Dual Sentiment Validation:** *TextBlob* + *VADER* (72.94% label agreement) for high-confidence training data.  
- **Modeling:** *Logistic Regression (92.37% accuracy)*, benchmarked against *BERT* and *DistilBERT*.  
- **Feature Insights:** *Dominance analysis* identified top satisfaction drivers:  
  - Value for Money  
  - Ground Service  
  - Seat Comfort  
- **Automation:** Full-stack **Python pipeline** for scraping → cleaning → sentiment labeling → modeling → visualization.  

---

## 🛠️ Tech Stack
Python | Pandas | NumPy | Scikit-learn | SpaCy | TextBlob | VADER | BeautifulSoup | Requests | HuggingFace Transformers | Dominance-Analysis | Matplotlib | Seaborn | WordCloud

---

## 📊 Methodology
Follows the **CRISP-ML(Q)** framework for quality-controlled machine learning:
1. **Data Acquisition:** Automated Python web scraping of 127K+ reviews from AirlineQuality.com  
2. **Data Cleaning:** Emoji demojizing, chatword expansion, stopword & punctuation removal, stemming with SpaCy  
3. **Sentiment Labeling:** Dual lexicon agreement validation using VADER & TextBlob  
4. **Modeling:** TF-IDF vectorization + Logistic Regression; compared with BERT and DistilBERT  
5. **Prescriptive Analytics:** Dominance analysis for feature-level impact ranking  
6. **Pipeline Automation:** End-to-end Python workflow integrating scraping, preprocessing, and model execution  

---

## 📈 Model Performance
| Model | Accuracy |
|--------|-----------|
| Logistic Regression | **92.37%** |
| BERT | 88.00% |
| DistilBERT | 90.08% |

---

## 📌 Results
- Fully automated sentiment pipeline achieves **>92% accuracy** with interpretable results.  
- Dominance analysis highlights key improvement areas: *Value for Money, Ground Service, Seat Comfort*.  
- Pipeline design is **scalable and reusable** for hospitality, retail, and customer-experience domains.  

---

## 📚 Author
**Rohit Anand**  
MBA – Business Analytics | University of Hyderabad  
[LinkedIn](https://linkedin.com/in/rohit-anand) | [Email](mailto:your.email@example.com)

---

## 🧩 Future Work
- Expand scraping to multilingual reviews  
- Integrate aspect-based sentiment analysis (ABSA)  
- Add real-time API data streaming  
- Deploy as an interactive Streamlit/Power BI dashboard  
