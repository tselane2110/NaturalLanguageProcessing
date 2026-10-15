# Urdu-Binary Sarcasm Detection:

* `notebook.ipynb` includes all the work done from data preprocessing to model training (including markdown-based explanation).
* `projectGuidelines.pdf` is the document containing the assignment guidelines.
* `urdu_sarcastic_dataset.csv` is the provided dataset used for the assignment.

The following table concludes the achieved results:

| **Model** | **Precision (label = 0)** | **Precision (label = 1)** | **Overall Accuracy** |
| :--- | :--- | :--- | :--- |
| LogisticRegression-DS1 | 84.81% | 72.33% | 79.27% |
| SVM-DS1 | 84.75% | 72.52% | 79.34% |
| LogisticRegression-DS2 | **85.06%** | 74.48% | **80.51%** |
| SVM-DS2 | **85.23%** | 74.33% | **80.51%** |
| BiLSTM | 81.11% | **77.26%** | 79.68% |
| <b><u>XLM-RoBERTa</u></b> | <b><u>85.38%</u></b> | <b><u>78.15%</u></b> | <b><u>82.43%</u></b> |
