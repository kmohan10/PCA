# PCA
PCA on Orthopaedic data having 6 Features

The objective of PCA is to reduce the number of Dimensions/Features in a dataset. This new dataset with fewer dimensions will help reduce the computation and complexity of the model we build.

For this example, we will use the Orthopeadic dataset which has 6 Features and 1 dependent class.

First we will perform PCA on the data to reduce its Dimensions
Next, using the dataset with fewer Dimensions, we will build a KNN Classification model.
Finally, we will compare the performance of the KNN Classification Model using the original dataset which was 0.822 versus the KNN Classification Model using the dataset after PCA.
