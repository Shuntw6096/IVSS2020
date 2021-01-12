# Intelligent-Video-Surveillance-Systems
NTUST-ECE Intelligent Video Surveillance Systems 2020 Fall

---

### HW1
Please use CIFAR 10 datasets
1. Use K nearest neighbors Algorithm in python and scikit-learn
2. Use a neural network to perform image classification by pytorch and show the training procedure by tensorboard

### HW2
Please write image classifiers  for Dog and cat datasets by Python OpenCV
1. Find Dog and Cat datasets from Kaggle.com, [link](https://s3.amazonaws.com/content.udacity-data.com/nd089/Cat_Dog_data.zip)
2. Use Histogram of oriented Gradient (HOG) from OpenCV  as your feature
3. Use a support vector machine as your classifier
4. Visualize your HOG descriptor

References：
1. [HOG](https://github.com/tobybreckon/python-examples-cv/blob/master/hog.py)
2. [HOG with SVM classifier](https://www.kaggle.com/manikg/training-svm-classifier-with-hog-features)
3. [Object Detection](https://github.com/SamPlvs/Object-detection-via-HOG-SVM)

### HW3
Please generate optical flow image  from a pair of images (from open flow benchmark images  ) by using the following four approaches by using OpenCv or deep neural networks. I use [Kitti](https://s3.eu-central-1.amazonaws.com/avg-kitti/raw_data/2011_09_26_drive_0005/2011_09_26_drive_0005_sync.zip).
1. Lucas-Kanarese approach constant flow 
2. Farneback optical flow
3. Deep Learning approach by FLOWNET2
4. Your results should use colors to encode the direction of the optical flow
5. Please show both estimated flow and ground truth flow

References：
1. [Optical flow](https://nanonets.com/blog/optical-flow/)
2. [Optical flow using neural networks](https://towardsdatascience.com/generating-optical-flow-using-nvidia-flownet2-pytorch-implementation-d7b0ae6f8320)

### HW4
Babysitting your finetune procedure, please finetune the semantic segmentation model for [Synthia  dataset](http://synthia-dataset.net/downloads/) or [Synthia-SF  dataset](http://synthia-dataset.net/download-synthia-sf/).
1. You can pick your reference pre-trained models from [Pytorch semantic segmentation models](https://github.com/qubvel/segmentation_models.pytorch)
2. Please use the tensorboard to show your loss function
3. Please use the test datasets to assess the accuracy of your model
