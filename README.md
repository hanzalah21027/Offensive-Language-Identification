# Offensive Language Identification

We go through a detailed study of Offensive Language Identification using Deep Learning techniques. Attached Report [Report.pdf](https://github.com/hanzalah21027/Offensive-Language-Identification/blob/main/Report.pdf) details the analysis.

## Methodology

We have used four methods to train our datasets.\
Each of the methods is described below:
### TF-IDF model
TF-IDF or Term Frequency - Inverse Document
Frequency algorithm uses the frequency of words
to determine their relevancy to a given document.
The process to classify words as offensive or not
offensive using TF-IDF was carried out as follows:
1. Performed pre-processing of data
2. Tokenized words and count frequencies
3. Found TF and IDF for words
4. Vectorized vocabulary
5. Passed vectors to a classifier such as SVM or
Logistic Regression to get the labels


### BERT-based models
BERT, or Bidirectional Representation for Transformers, was proposed by researchers at Google
AI in 2018. BERT has state-of-the-art accuracy in
performing various NLP tasks, such as classification or question-answer tasks.
The following tasks were performed while evaluating BERT-based models:
1. Performed pre-processing of data
2. Imported various BERT models from Hugging Face
3. Fined-tuned BERT models with classification
head
4. Performed hyperparameter tuning of models
5. Tried different BERT models to evaluate results
6. Trained different datasets containing hate
speech and offensive text
7. Tried stacked ensembling using 5 different
BERT classifiers trained on various datasets
containing hate speech and offensive text

### Stacking Ensemble
Stacking, also known as Stacked Generalization,
is an ensemble machine-learning technique. It
combines the prediction of multiple machine learning models on the same dataset.

### Neural Architecture Search
The neural architecture search is used to discover
the best neural network architecture for a specific
need. NAS automates the human effort to find
the best neural architecture.


## Results
![image](https://user-images.githubusercontent.com/88739322/219786894-f0323ba6-e0ad-40c5-86dc-3aa324fc96cd.png)
