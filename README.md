# 🔫 Public Perception on Mass Shootings (2010–2023)

**Author:** Rohit Khilare  

---

## 📘 Project Overview

This project presents a **comprehensive analysis of mass shootings in the U.S. from 2010 to 2023**, with a dual focus:
- Quantitative analysis of mass shooting data
- Qualitative sentiment and opinion mining from three politically varied media sources: **CNN**, **Epoch Times**, and **New York Times**

The project investigates public perception, press bias, trends, geographical spread, and victim profiles to better understand the narrative and causes behind mass shootings.

---

## 🔍 Key Research Questions

- 📈 What is the **trend** in number and severity of mass shootings?
- 📰 What is the **general opinion** of major news outlets?
- 🧭 What are the **differences in perception** across CNN, Epoch, and NYT?
- 🌍 Are there **geographic patterns** in shootings?
- ⚰️ What are the trends in **casualty and victim distribution**?
- ❓ What could be the **potential reasons** for divergent narratives?

---

## 🧪 Methodology

### 📊 Quantitative Analysis
- Cleaned and processed a CSV dataset (`data-project.csv`) of U.S. mass shootings
- Performed:
  - **Trend Analysis** (line plots)
  - **Casualty Distributions** (histograms & boxplots)
  - **Correlation Matrix** (fatalities, injuries, age, etc.)
  - **Geographic Distribution** (count plots)
  - **Weapon Use Analysis** (bar charts)
  - **Victim Analysis** (boxplots)

### 🧠 NLP & Sentiment Analysis
- Processed article text from:
  - `CNN.txt`
  - `Epoch.txt`
  - `New York Times.txt`
- Used **VADER Sentiment Analysis** to compare media tone
- Created **word clouds** for press framing and narrative cues

---

## 📌 Findings

### 🔁 Trends
- Sharp **rise in frequency** of mass shootings since 2010
- Some peak years include **2016, 2017, and 2022**

### 🌎 Geography
- **Texas, California, Florida, and Illinois** recorded the highest number of incidents
- Southern and Western states dominate the statistics

### 📉 Casualty Distribution
- Casualties vary widely, with some high-profile incidents showing fatalities above 50
- Distribution is skewed, with many low-casualty incidents and a few very deadly ones

---

## 📰 Press Sentiment Summary

| Source       | Sentiment | Narrative Focus                                                                 |
|--------------|-----------|----------------------------------------------------------------------------------|
| **CNN**      | Neutral   | Focuses on gun control, legislation, and emotional toll of mass shootings        |
| **Epoch**    | Positive  | Emphasizes **mental health**, **antidepressants**, and **gun-free zones**       |
| **NY Times** | Negative  | Emphasizes the U.S.’s **high gun ownership** and lack of regulation              |

### 🧾 Word Cloud Analysis
- **CNN:** Frequent mentions of “violence”, “community”, “safety”
- **Epoch:** Frequent mentions of “mental health”, “SSRI”, “gun-free zones”
- **NY Times:** Repeats “guns”, “ownership”, “mass shootings”, “regulation”

---

## 📈 Visual Samples

- Mass Shootings by Year (2010–2023)
- Fatality Distribution
- Correlation Matrix
- Word Clouds by Source
- Sentiment Bar Chart by Source
- Statewise Shooting Counts
- Weapon Usage Bar Chart

---

## 📦 Dataset

- Source: CSV file with mass shooting records from 2010–2023
- Fields: `date`, `location`, `fatalities`, `injured`, `weapon_details`, `age`, etc.
- Textual Data: Manually curated media narratives from CNN, Epoch Times, and NYT

---

## 🛠️ Tools & Technologies

- Python (Pandas, Seaborn, Matplotlib, NLTK, WordCloud)
- Natural Language Toolkit (VADER Sentiment Analyzer)
- Jupyter Notebook / Python Script
- Manual data cleaning and preprocessing

---

## ✅ Recommendations

**For Policymakers:**
- Implement tighter gun control laws
- Monitor and address SSRI/antidepressant overprescription

**For Communities:**
- Increase mental health accessibility and trauma counseling
- Foster community engagement to combat isolation

**For Media:**
- Promote balanced, fact-based reporting without politicizing trauma
- Collaborate with experts to avoid misinformation

---

## ⚠️ Limitations

- Potential bias in media source selection and coverage
- Missing values and inconsistencies in historical shooting data
- Sentiment analysis doesn’t fully capture sarcasm, nuance, or tone

---

## 🧠 Future Work

- Expand dataset with real-time scraping (e.g., Gun Violence Archive)
- Incorporate Reddit/Twitter public sentiment for deeper analysis
- Use topic modeling (LDA) and advanced NLP methods
- Build an interactive dashboard using Streamlit or Power BI

---

> *This project addresses a deeply complex and tragic societal issue through a mix of data science, media analysis, and empathy. It offers actionable insights and encourages responsible conversation in an increasingly polarized space.*

