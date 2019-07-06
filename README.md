# Real Time object detection 

Recently, I fiinshed my course on Udemy which deals with  deep learning using convolution nueral networks. It offered great practical and theoritical knowledge in this area. Hence I recommennd any of the beginners like me who wants to get hands on experience and knowledge on deep learning can try out the course on Udemy.

##  Steps of Execution : 

1. Initially reach out to this link https://github.com/tensorflow/models/tree/master/research/object_detection, under Table of contents, Setup section, click on Installation sub section.
This section basically deals with libraries required to run the objection detection. Install all and proceed.

2. Along with the other libraries you may need to install Protobuf 2.6 
It is a method of serializing structured data. It is useful in developing programs to communicate with each other over a wire or for storing data. You ca download this from here https://github.com/protocolbuffers/protobuf/releases/tag/v3.8.0.  I have used protoc-3.8.0-win64.zip.

3. Download the pre-trained default models from  https://github.com/tensorflow/models. Make sure you put all the folders under a commom folder


4. Complitation of Protobuf library,open your Anaconda prompt ,change the directory to the place where you have kept both the folders ,then do[change directory] cd models/research and then give this command consisting of full path were your protoc.exe file is located followed by [protoc object_detection/protos/*.proto — python_out=.].
For e.g. [C:/Users/ADMIN/tf_obj_det/protoc-3.4.0-win32/bin/protoc object_detection/protos/*.proto — python_out=. ],here tf_obj_det is the folder in which I have kept models and protoc file after unzipping.

5. Run the real-time-object-detection.ipynb 
