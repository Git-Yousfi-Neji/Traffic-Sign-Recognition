# Traffic-Sign-Recognition
Traffic signs detection and classification
Abstract
Convolutional neural networks are the most widely used deep learning algorithms for traffic signal classification till date but they fail to capture pose, view, orientation of the images because of the intrinsic inability of max pooling layer.This paper proposes a novel method for Traffic sign detection using deep learning architecture called capsule networks that achieves outstanding performance on the German traffic sign dataset.Capsule network consists of capsules which are a group of neurons representing the instantiating parameters of an object like the pose and orientation by using the dynamic routing and route by agreement algorithms.unlike the previous approaches of manual feature extraction,multiple deep neural networks with many parameters,our method eliminates the manual effort and provides resistance to the spatial variances.CNNs can be fooled easily using various adversary attacks and capsule networks can overcome such attacks from the intruders and can offer more reliability in traffic sign detection for autonomous vehicles.Capsule network have achieved the state-of-the-art accuracy of 97.6% on German Traffic Sign Recognition Benchmark dataset (GTSRB).

Steps to run
1)Install all the dependencies
Tensorflow,Keras,Numpy,Pandas,Pickle,Matplotlib
2)Run the ipython notebook file traffic_sign_classification_TRAINING_CODE.ipynb using jupyter notebook
