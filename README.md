# Fake Audio Detection using SceneFake Dataset 🎧🔍

## 📝 Project Overview

This project focuses on detecting fake audio clips using machine learning models. We use the [SceneFake Dataset](https://www.kaggle.com/datasets/mohammedabdeldayem/scenefake/data?select=eval) from Kaggle, which contains both real and synthetic (fake) audio samples. The goal is to build a classification model capable of identifying whether an audio file is real or fake based on extracted audio features.

---

## 📂 Dataset

**Source:** [SceneFake Dataset on Kaggle](https://www.kaggle.com/datasets/mohammedabdeldayem/scenefake/data?select=eval)

**Structure:**
- `train/`: Contains real and fake audio files used for training.
- `eval/`: Contains audio files used for evaluation.
- Each audio file is in `.wav` format.

---

## 🧰 Libraries Used

Ensure you have the following Python libraries installed:

```bash
pip install numpy pandas librosa matplotlib seaborn scikit-learn
