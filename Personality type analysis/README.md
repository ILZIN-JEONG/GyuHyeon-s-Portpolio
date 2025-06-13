# 🧠 Extrovert vs. Introvert: Are Extroverts More Active Online Too?

This project explores the relationship between personality type and behavioral tendencies in both offline and online spaces, using the **Extrovert vs. Introvert Behavior Data** from Kaggle.

---

## 📌 Project Overview

- **Dataset:** [Extrovert vs. Introvert Behavior Data](https://www.kaggle.com/datasets/)
- **Goal:** Investigate how extroverts and introverts behave differently across:
  - **Offline activity**: measured by `Social_event_attendance`
  - **Online expression**: measured by `Post_frequency`

---

## 🎯 Objectives

- Do extroverts post more frequently on social media than introverts?
- Are introverts more expressive online than they are offline?
- Does the correlation between online and offline behavior differ by personality type?

---

## 🔧 Data Preprocessing

- Missing values in numeric columns were filled using **mean** or **median**.
- Categorical missing values were filled using the **mode**.
- Text data was cleaned (stripped and lowercased) for consistency.

---

## 📊 Key Analyses

### 1. Activity Distribution (Boxplot)
- Extroverts tend to attend more offline events.
- Posting frequency varied within both groups.

### 2. Correlation Between Online and Offline Activity

| Group      | Correlation (Post vs Social) | Interpretation |
|------------|-------------------------------|----------------|
| **Overall**    | `+0.727`                        | Strong positive correlation |
| **Introverts** | `+0.569`                        | Moderate correlation; some introverts post frequently |
| **Extroverts** | `+0.365`                        | Weak correlation; not all extroverts are active online |

---

## 📈 Visualizations

Visualizations were created using **Plotly** for interactivity:

- 📊 **Scatter Plot:** Online vs Offline activity by personality  
- 📦 **Boxplot:** Post frequency and event attendance distribution  
- 🔥 **Heatmaps:** Correlation matrices (overall, introverts, extroverts)

> All charts are interactive and optimized for browser viewing.

---

## 🧠 Key Takeaways

- While extroverts are more socially active offline, **not all of them post more online**.
- Some introverts are **highly expressive online**, suggesting digital platforms may provide a more comfortable space for expression.
- Personality type influences the relationship between online and offline activity.

---

## 💾 Resources

- 📘 Kaggle Notebook: [Insert your notebook link here]
- 📂 Dataset: [Extrovert vs. Introvert Behavior Data](https://www.kaggle.com/datasets/)
- 📊 Visualizations: Built with `pandas` and `plotly`

---

## 📎 License

This project is for educational purposes only.  
Dataset sourced from [Kaggle](https://www.kaggle.com/).
