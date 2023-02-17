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
