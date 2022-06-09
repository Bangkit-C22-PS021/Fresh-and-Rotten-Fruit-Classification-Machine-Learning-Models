# Fresh and Rotten Fruit Classification Machine Learning Models
The Machine Learning (ML) model in this folder is a model that functions to detect whether the fruit is fresh or rotten. The dataset used in making this model is sourced from the Kaggle website, namely [Fruits fresh and rotten for classification](https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification) created by SRIRAM REDDY KALLURI. This model was created via Google Colab using TensorFlow version 2.8.0. Fruits that can be detected through this ML Model include Apples, Bananas and Oranges. This model uses the Image Classification method through the camera used in the device in the application that contains this ML model to obtain detection results. In this model, some use only a few Image Augmentation parameters and some use more Image Augmentation parameters to get various detection angles. The difference for the two types of Image Augmentation parameters comes from the file name used where the Model that uses the Image Augmentation parameter mostly uses the description 'with Image Augmentations'. In this model, the categories obtained from the detection results using the ML Model are only two classification categories, including:


* Fresh Fruit
* Rotten Fruit


From the results of the exploration of various parameters and pre-trained models, we found the four best models in our opinion, including:


* [Fresh and Rotten Fruit Classification with CNN Model]
* [Fresh and Rotten Fruit Classification CNN Model with Image Augmentations] 
* [Fresh and Rotten Fruit Classification with MobileNetV2 Model]
* [Fresh and Rotten Fruit Classification MobileNetV2 Model with Image Augmentations]


From the two best model results, the results of training accuracy, validation accuracy and test accuracy are around 99%. In addition, the four models have also been tested on images that have never been seen before, these test images were obtained through Google Images and produced fairly accurate predictions.
