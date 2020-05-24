# tensorflow-object-detection-api-configuration
This tutorial discusses how to configure the Tensorflow Object Detection API in windows and how implement custom object detection.

## Credits & Links

1. [Download Tensorflow Object Detection API](https://github.com/tensorflow/models)
2. [How to install Tensorflow Object Detection](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md)

## Installing the Tensorflow Object Detection API

1. Download the tensorflow object detection api from [Github](https://github.com/tensorflow/models)
2. Open the Anaconda Prompt and install the dependencies for windows,

```
pip install tensorflow
pip install Cython
pip install contextlib2
pip install pillow
pip install lxml
pip install jupyter
```

3. Download the files from this repository
4. Copy and paste ```protoc.exe``` file in the path ```models-master\research```
5. Open the Commmand Prompt in ```models-master\research``` and copy and run the command included in ```protoc command.txt```
6. Copy the files ```object_detection_tutorial.ipynb```, ```1.0 Customized Object Detection.ipynb``` & ```1.1 Customized Object Detection-Video.ipynb``` into ```models-master\research```
7. Run above codes and check

## Models used in Tensorflow Object Detection API

![Models used in Tensorflow Object Detection API](https://cdn-images-1.medium.com/max/800/1*-EyxSs2OiyWm-E6MSpSJiA.png)
