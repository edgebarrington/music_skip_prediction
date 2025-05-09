# 🎵 Music Skip Prediction

This project explores the development of machine learning models to predict **whether a user will skip a track** on a music streaming platform based on audio features and user behavior data.

---

## 📌 Project Goals

- Predict skip behavior using time-series or deep learning models (RNN, Transformer).
- Analyze how acoustic properties like tempo, mood, and energy affect skipping.
- Optionally: compare sober vs. intoxicated listener reactions (future scope).

---

## 📂 Project Structure

```bash
music_skip_prediction/
├── data/                   # Raw and preprocessed datasets
├── notebooks/              # Jupyter notebooks for EDA, modeling
├── src/                    # Core Python scripts/modules
│   ├── data_preprocessing.py
│   ├── model.py
│   └── utils.py
├── requirements.txt        # Dependencies
├── README.md               # This file
└── .gitignore              # Files/folders to ignore
