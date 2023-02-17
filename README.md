# Analysis of traditional and deep learning methods on Malaria Detection from Image Cells

We go through a detailed study of traditional Machine Learning algorithms for malaria detection. Attached Report details the analysis.

The Dataset can be found here [Dataset]().

## Methodology

We have used various filters such as edge detection algorithms, namely, Canny, Sobel and Scharr, and Adaptive Histogram Equalization, also known as CLAHE. We have also used Global feature extraction, which finds features based on shape, texture and, colour histogram, and local feature extraction techniques such as SIFT (Scale-Invariant Feature Transform) and KAZE. We have then applied our three baseline machine learning models to our processed data, namely, Decision Tree, Logistic Regression and, Support Vector Machine.
We then performed Ensembling on the best performing models, using different bagging and boosting techniques such as Random Forest and Adaboost for hyperparameter tuning of our models. Further, we delved into Deep Learning, where we first used ANN(Artificial Neural Network). We then applied CNN (Convolution Neural Network) on our dataset using different pre-trained VGG models, such as VGG-11, VGG-13, VGG-16 and VGG-19, with ReLU(Rectified linear unit) as our activation function.
