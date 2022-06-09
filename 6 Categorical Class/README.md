# Fresh and Rotten Fruit Classification Machine Learning Models
The Machine Learning (ML) model in this folder is a model that functions to detect whether the fruit is fresh or rotten. The dataset used in making this model is sourced from the Kaggle website, namely [Fruits fresh and rotten for classification](https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification) created by SRIRAM REDDY KALLURI. This model was created via Google Colab using TensorFlow version 2.8.0. Fruits that can be detected through this ML Model include Apples, Bananas and Oranges. This model uses the Image Classification method through the camera used in the device in the application that contains this ML model to obtain detection results. This model uses several Image Augmentation to obtain various detection angles. The categories obtained from the detection results using the ML Model are divided into six categories including:


* Fresh Apples
* Rotten Apples
* Fresh Oranges
* Rotten Oranges
* Fresh Bananas 
* Rotten Bananas


From the results of the exploration of various parameters and pre-trained models, we found the two best models in our opinion, including:


* [Fresh and Rotten Fruit Classification with CNN Model](https://github.com/Bangkit-C22-PS021/model-ml-fruit-fresh/blob/main/6%20Categorical%20Class/Fresh-and-Rotten-Fruit-Classification-CNN/Fresh_and_Rotten_Fruit_Classification_CNN_Model.ipynb)
* [Fresh and Rotten Fruit Classification with MobileNetV2](https://github.com/Bangkit-C22-PS021/model-ml-fruit-fresh/blob/main/6%20Categorical%20Class/Fresh-and-Rotten-Fruit-Classification-MobileNetV2/Fresh_and_Rotten_Fruit_Classification_MobileNetV2_Model.ipynb)


From the two best model results, the results of training accuracy, validation accuracy and test accuracy are around 99%. In addition, the two models have also been tested on images that have never been seen before, these test images were obtained through Google Images and produced fairly accurate predictions.
