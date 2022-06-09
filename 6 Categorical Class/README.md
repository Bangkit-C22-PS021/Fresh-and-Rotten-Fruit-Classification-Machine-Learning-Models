# Fresh and Rotten Fruit Classification Machine Learning Models
The Machine Learning (ML) model in this folder is a model that functions to detect whether the fruit is fresh or rotten. Fruits that can be detected through this ML Model include Apples, Bananas and Oranges. This model uses the Image Classification method through the camera used in the device in the application that contains this ML model to obtain detection results. This model uses several Image Augmentation to obtain various detection angles. The categories obtained from the detection results using the ML Model are divided into six categories including:


* Fresh Apples
* Rotten Apples
* Fresh Oranges
* Rotten Oranges
* Fresh Bananas 
* Rotten Bananas


From the results of the exploration of various parameters and pre-trained models, we found the two best models in our opinion, including:


1. Fresh and Rotten Fruit Classification with CNN Model
2. Fresh and Rotten Fruit Classification with MobileNetV2


From the two best model results, the results of training accuracy, validation accuracy and test accuracy are around 99%. In addition, the two models have also been tested on images that have never been seen before, these test images were obtained through Google Images and produced fairly accurate predictions.
