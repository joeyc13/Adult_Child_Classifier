# Adult_Child_Classifier
ML model to classify images of adults and children

Dataset source is from Kaggle user IRON486 at the below url:

https://www.kaggle.com/datasets/die9origephit/children-vs-adults-images

The dataset contains 2 classes, Adults and Children. Dataset was split into training and test sets with a test_train_split ratio of 0.15. The training dataset contains 680 images and the test dataset contains 120 images. 
Images have a resolution of 370 x 320 pixels in RGB color. For methodology of data collection see source in the above url.

Model was created using Tensorflow and associated APIs such as Numpy and Matplotlib.

On initial implementation the model achieved ~70% accuracy on the test set and is able to classify images to relatively high degree of accuracy.
