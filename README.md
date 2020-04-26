# Covid-19
The repository  holds the working on classification of normal and infected x-rays of lungs. 

Objectives: 
Write code for detecting infections such as COVID-19 among X-Ray images: 

1) Use CNN, pre-trained on ImageNet, to extract basic features from X-Ray images.
2) Train the classification layers in order to detect instances of Infected (COVID-19 + Pneumonia) and Normal X-Ray images.
Fine-tune the entire network to try to improve performance.

Chest X-Ray Images Dataset
Background:
New studies [1] have revealed that the damage done to lungs by infections belonging to the family of coronaviruses (COVID-19, SARS, ARDS etc.) can be observed in X-Ray and CT scan images. With a worldwide shortage of test kits, it is possible that careful analysis of X-Ray and CT scan images may be used in diagnosis of COVID-19 and for the regular assessment while they are recovering. In this assignment, we will use an open source dataset of X-Ray images and train a Convolutional Neural Network to try and detect instances of infections containing COVID-19 and Pneumonia.

## Dataset Details: 
This dataset contains X-Ray images from 2 classes:
Class: Infected & Normal
In total there are 12000 Training, 1500 Validation and 1500 Testing samples.
Two Models are used with pytorch VGG16 & resnet18
The link for datset is as follows:
https://drive.google.com/file/d/1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK/view
## VGG16
With pretrained model Testing results are:

True Normal: 877
True Infected: 571
False Normal: 44
False Infected: 8
Precision: 0.9522258414766558
Recall: 0.9909604519774011
F1 Score: 0.9712070874861573
Accuracy of the network on the images: 96 % 

## resnet18
With pretrained model Testing results are:
True Normal: 873
True Infected: 592
False Normal: 23
False Infected: 12
Precision: 0.9743303571428571
Recall: 0.9864406779661017
F1 Score: 0.9803481190342505
Accuracy of the network on the images: 97 %



## Report
Details of the project are in Report.pdf.
