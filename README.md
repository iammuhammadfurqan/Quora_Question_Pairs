# Quora Question Pairs Analysis

[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue?style=for-the-badge&logo=github)](https://github.com/iammuhammadfurqan)
[![Kaggle](https://img.shields.io/badge/Kaggle-Profile-blue?style=for-the-badge&logo=kaggle)](https://www.kaggle.com/muhammadfurqan0)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/immuhammadfurqan/)
[![Gmail](https://img.shields.io/badge/Gmail-Contact%20Me-red?style=for-the-badge&logo=gmail)](mailto:sheikhfurqan048@gmail.com)

## Overview

This project explores the Quora Question Pairs dataset to identify whether two questions are semantically similar. It involves natural language processing (NLP) techniques and machine learning models to predict the similarity between questions effectively.

## Dataset Description

The dataset includes pairs of questions from Quora and their similarity labels. Below are the key columns:

- **id**: Unique identifier for each question pair.
- **qid1, qid2**: Unique identifiers for individual questions.
- **question1, question2**: Text of the two questions to compare.
- **is_duplicate**: Target variable indicating whether the questions are duplicates (1) or not (0).

This dataset is ideal for NLP tasks and for building classification models to predict question similarity.

## Methodology

The notebook follows these steps:

1. **Data Exploration**: Analyzing the distribution of duplicate and non-duplicate pairs, and understanding the dataset structure.
2. **Preprocessing**: Cleaning text, tokenization, stemming/lemmatization, and removing stop words.
3. **Feature Engineering**: Creating features like TF-IDF, word overlap, and cosine similarity.
4. **Model Training**: Implementing models like Logistic Regression, SVM, and Neural Networks.
5. **Evaluation**: Using metrics like accuracy, F1-score, and AUC-ROC to assess model performance.
6. **Conclusion**: Summarizing results and discussing potential improvements.

## Requirements

The following libraries are required:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- nltk
- gensim

Install them using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk gensim
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/iammuhammadfurqan/Quora-Question-Pairs.git
   ```
2. Open the notebook in Jupyter or a compatible IDE.
3. Run all cells sequentially to reproduce the analysis.

## Results

The project demonstrates effective methods for identifying duplicate questions. It highlights the importance of feature engineering and the power of NLP in tackling real-world challenges.

## Contributions

Contributions are welcome! Fork the repository, make your changes, and submit a pull request to enhance this analysis.

## Contact

For queries or collaboration, reach out via:

- Email: [sheikhfurqan048@gmail.com](mailto:sheikhfurqan048@gmail.com)
- LinkedIn: [Muhammad Furqan](https://www.linkedin.com/in/immuhammadfurqan/)

---
Thank you for exploring this project!

