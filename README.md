## Face Detection Pipeline using HOG Feature Extraction

As we all know, real world datasets are very noisy and heterogeneous, and may have missing features, and the data may not be clean so that it can directly be used to train a Machine Learning Model. Instead, data needs to be cleaned and made in a form so that it can be consumed by a down-stream model. We also might need to extract some features from the data.

One interesting and compelling application of machine learning is to images. In the real world, data is rarely so uniform and simple pixels will not be suitable and hence we need a way to extract features from these images. One such feature extraction technique is Histogram of Oriented Gradients (HOG), which transforms image pixels into a vector representation that is sensitive to broadly informative image features regardless of confounding factors like illumination.

**The goal of this notebook/project is to develop a simple face detection pipeline and train a SVM Model to detect faces in images.**