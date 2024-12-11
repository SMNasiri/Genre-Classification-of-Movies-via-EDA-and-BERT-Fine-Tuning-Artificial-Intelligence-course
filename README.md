# Genre-Classification-of-Movies-via-EDA-and-BERT-Fine-Tuning-Artificial-Intelligence-course
Genre classification of Persian and English movies using exploratory data analysis (EDA) and fine-tuning BERT-based models (ParsBERT and BERT). The project involves preprocessing movie metadata, conducting statistical analyses, and training language models for text classification.

This project focuses on classifying movie genres using metadata and summaries in Persian and English. It combines exploratory data analysis (EDA) and fine-tuning of BERT-based models, leveraging the rich textual data to achieve accurate genre predictions.

---

## **Project Objectives**
1. **Exploratory Data Analysis (EDA)**:
   - Perform data cleaning and preprocessing.
   - Analyze statistical properties of the dataset, including genre distribution, correlations, and time-based trends.
   - Visualize data to understand key features and relationships.

2. **Text Classification**:
   - Fine-tune language models (ParsBERT for Persian data and BERT for English data).
   - Classify movie genres based on summaries using Full Fine-Tuning.

---

## **Dataset**
The dataset (`persianmovies.csv`) contains metadata for Persian and English movies, including:
- Movie title.
- Production year.
- Genre labels.
- Textual summaries (in Persian and English).

---

## **Methodology**
1. **Data Preprocessing**:
   - Handle missing and null values.
   - Balance the dataset by adjusting over- and under-represented genres.
   - Split the dataset into training and test subsets using a fixed random seed for reproducibility.

2. **Exploratory Data Analysis (EDA)**:
   - Perform univariate and multivariate analyses.
   - Generate visualizations such as genre distributions, correlations, and time-based trends.

3. **Model Training**:
   - Fine-tune `ParsBERT` on Persian text data.
   - Fine-tune `BERT` on English text data.
   - Compare results for preprocessed and unprocessed datasets.

4. **Evaluation**:
   - Measure accuracy, precision, recall, and F1 score.
   - Analyze the impact of preprocessing on model performance.

