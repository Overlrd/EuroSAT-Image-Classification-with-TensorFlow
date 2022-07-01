# Satellite-Image-Classification-With-Tensorflow
 Perform image classification on satellite data (EuroSAT) using TensorFlow
 
 Satellite imagery is important for many applications including disaster response, law enforcement, and environmental monitoring. These applications require the manual identification of objects and facilities in the imagery.
Satellite image classification is undoubtedly crucial for many applications in agriculture, environmental monitoring, urban planning, and more. Applications such as crop monitoring, land and forest cover mapping are emerging to be utilized by governments and companies, and labs for real-world use.

In this Notebook i used the EffecientNet V2 model to perform classification on the EuroSAT dataset based on Sentinel-2 satellite images covering 13 spectral bands. It consists of 27,000 labeled samples of 10 different classes: annual and permanent crop, forest, herbaceous vegetation, highway, industrial, pasture, residential, river, and sea lake.
![Image_1](https://github.com/Overlrd/Satellite-Image-Classification-With-Tensorflow/blob/main/class_samples.png)

The EffecientNet V2 model is highly accurate on most of the classes.
It reached 100% accuracy on residential class and the class with lower accuracy is pasture with 93%.

![image_2](https://github.com/Overlrd/Satellite-Image-Classification-With-Tensorflow/blob/main/confusion-matrix.png)




In all 64 images from the mode prediction 3(red labels in the image) are False.
Our model can still be improved.


![image_2](https://github.com/Overlrd/Satellite-Image-Classification-With-Tensorflow/blob/main/predicted-sample-images.png)

