# TabPFN – Katabatic Contribution (Zaid)

## 🔍 About
This repository contains my contribution to the Katabatic project using the TabPFN zero-shot model. It was tested on:
- Breast Cancer dataset → 97.66% accuracy
- Adult Income dataset → 85.53% accuracy

## 📁 Files
- `tabpfn_model.ipynb`: Colab notebook used to run TabPFN
- `evaluation_results.csv`: Final accuracy scores
- `README.md`: Explanation and context for this contribution

## 🧠 Contribution Summary
TabPFN is a transformer-based classifier suitable for small tabular data. It fits Katabatic’s research goals by offering a pretrained, zero-shot classifier for benchmarking real vs synthetic datasets using TSTR evaluation.

## 🧪 Notes
- The Adult dataset was cleaned and limited to 10,000 rows for TabPFN compatibility
- TabPFN complements GANBLR’s Bayesian logic with a transformer-based Bayesian meta-learning model
