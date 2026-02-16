# Reddit Post Moderation System
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

### *Automated Moderation Pipeline using Random Forest & Gemini 2.0 Flash*

This project implements an end-to-end Machine Learning pipeline to classify Reddit posts as **Safe** or **NSFW** (Not Safe For Work). It leverages SQL for analysis, Random Forest for high-precision classification, and **Google's Gemini 2.0 Flash API** to handle complex edge cases that traditional models miss.

## 🛠️Tech Stack
* **Languages:** Python, SQL (PandasQL)
* **Libraries:** Scikit-Learn, NLTK, Pandas, NumPy, Matplotlib, Seaborn
* **GenAI:** Google Generative AI (Gemini 2.0 Flash)

## Key Features
* **SQL Analysis:** Utilized `GROUP BY`, Window Functions, and `CASE` statements to analyze post virality.
* **EDA & Visualization:** Created correlation heatmaps and word clouds to understand NSFW triggers.
* **NLP Pipeline:** Implemented text cleaning, Stemming, Stopword removal, and **TF-IDF Vectorization** (Sparse Matrix).
* **Machine Learning:** Benchmarked **Decision Tree** vs. **Random Forest**, achieving an **F1-Score of 0.72**.
* **Generative AI Integration:** Deployed **Gemini 2.0 Flash** via API to re-evaluate edge cases, improving accuracy on complex slang/context.
