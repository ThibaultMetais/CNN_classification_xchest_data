# CNN_classification_xchest_data
A introduction to the image classification using Deep Learning (and more specifically CNNs).

The data can be found on Kaggle at this URL : https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia?rvi=1

Building the right model was about extract the info without overfitting : the resolution of the images can lead to a very complex model with a lot of parameters. Therefore, I used the strides within the convolutional layers as well as a limited number of filters.

An important point is the weird distribution of the different datasets : in order to obtain results with more sense, we moved some files in the notebook in order to have a decent validation dataset and to shuffle a bit the training and test ones.

We reach an accuracy of 90% that way.

Improvments : we could use transfer learning in order to solve the issue of the small amount of data provided in the dataset, using quite similar datasets available. Then, we could have incorporated it in our model to help it recognize some shapes, increasing the performances and reducing the overfitting.
