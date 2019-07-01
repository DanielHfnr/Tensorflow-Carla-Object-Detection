# Tensorflow-Carla-Object-Detection

With this repo you can train your own object detection classifier with the tensorflow object detection api. I use it to detect several objects in the Carla simulator. For this purpose I created my own dataset which can be downloaded from my other github repository. This is tested for Ubuntu 16.04 but should also work under windows and other linux distributions. 


#### Youtube demonstration video of the trained classifier:

[![Demonstration video](https://img.youtube.com/vi/08zke4oY7JE/0.jpg)](https://youtu.be/08zke4oY7JE)


A more detailed instruction on how to train this object detection classifier can be found under: [Link](https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10)

#### Basic steps to follow:

1. #### Install Tensorflow GPU support

   Go to the Tensorflow website and follow the step described [here](https://www.tensorflow.org/install). You will also need to install CUDA and cuDNN which is also described on the website.

2. #### Download Tensorflow object detection api 

   A detailed description can be found [here](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md).

3. #### Download this repository 

   Clone this repository into the ./tensorflow/models/research/object_detection/ folder.

4. #### Download the a pretrained model from TensorFlow's model zoo 

   To train the model you will need to use a pretrained model, otherwise training would consume to much time. I my case I used the Faster-RCNN-Inception-V2-COCO model and downloaded it from [Tensorflow's model zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md). Extract the pretrained model into the ./tensorflow/models/research/object_detection/ folder. 

5. #### Download dataset and copy files 

   Download the dataset from my other github repo and extract the images into the "images" of this repository e.g. ./tensorflow/models/research/object_detection/Carla_object_detection/images/

6. #### Generate training data 

7. #### Configure training  

8. #### Run training  

9. #### Export inference graph 

10. #### Use the trained classifier 
