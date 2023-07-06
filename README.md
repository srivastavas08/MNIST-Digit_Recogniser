# MNIST-Digit_Recogniser
Engineered by Keras and Trained on KNN

The MNIST digit recognizer project is a machine learning model designed to accurately classify handwritten digits from the popular MNIST dataset. In this specific implementation, the project utilizes Keras, a high-level neural networks API, for feature engineering, and the K-Nearest Neighbors (KNN) algorithm for training and classification.

Keras is employed to preprocess and enhance the raw input data, which consists of 28x28 pixel grayscale images of handwritten digits ranging from 0 to 9. The library assists in transforming the images into a suitable format for training the KNN model. Feature engineering techniques such as scaling, normalization, and dimensionality reduction are applied to improve the effectiveness of the model.

Once the preprocessing is complete, the KNN algorithm is trained on the preprocessed dataset. KNN is a non-parametric algorithm that classifies new data points based on their proximity to existing labeled data points. In this case, the KNN model compares the features extracted from the preprocessed images with the labeled images in the training set. The class label of the nearest neighbors is used to determine the final classification of the digit.

The combination of Keras for feature engineering and KNN for training provides a robust solution for digit recognition. By leveraging Keras' capabilities for data manipulation and KNN's ability to identify patterns in the data, the model achieves accurate predictions for handwritten digits. This project demonstrates the effectiveness of feature engineering techniques and the versatility of the KNN algorithm in image classification tasks.
