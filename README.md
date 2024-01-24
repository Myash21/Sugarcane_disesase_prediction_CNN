https://www.kaggle.com/datasets/nirmalsankalana/sugarcane-leaf-disease-dataset

Sugarcane disease prediction model built using custom CNN, link to kaggle dataset provided above.

Created a custom covnet with 3 convolutional layers followed by 4 dense layers.Utilized techniques like batchprocessing, dropout,
data augmentation(RandomContrast, RandomFlip(horizantal_and_vertical), RandomRotation as the dataset contained images taken from various different angles),
earlystopping to help prevent overfitting.
Implemented epoch wise learning rate decay which gives a smoother curve comparatively.
