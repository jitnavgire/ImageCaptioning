# ImageCaptioning
Image caption generator using deep learning Xception imagenet and LSTM model

# Motivation
*Self driving cars

*E-Commerce 

*CCTV cameras 

*Aid to the blind
![moti](https://user-images.githubusercontent.com/64503158/125403278-fea81e00-e3d2-11eb-8b2c-ffff15a7fc27.PNG)

# Dataset
We are using the Flickr 8k dataset which is provided by the University of Illinois at Urbana-Champaign.
This dataset contains 8000 images each with 5 captions.
It contain different files, one file containing the images with unique names and another file containing the image name and corresponding 5 captions.


# TextProcessing
One of the main steps in NLP is to remove noise so that the machine can detect the patterns easily in the text. 
Noise is present in the form of special characters such as hashtags, punctuation and numbers, Removing stop words.
‘startseq’ and ‘endseq’ added.
Generating the vocabulary which consists only unique words and assign unique number.
Encodes the captions with the corresponding number.

        Image Preprocessing
![feature](https://user-images.githubusercontent.com/64503158/125403625-59da1080-e3d3-11eb-8ccc-b6e28183c3c2.PNG)

        Methodology
![methodology](https://user-images.githubusercontent.com/64503158/125403817-94dc4400-e3d3-11eb-9539-22ae5f97aec1.PNG)
 
        ImageNet
![image](https://user-images.githubusercontent.com/64503158/125403966-b9d0b700-e3d3-11eb-9253-d090d83be4c5.png)


      Architecture
![image](https://user-images.githubusercontent.com/64503158/125404075-d836b280-e3d3-11eb-9d4d-4396e6263eb2.png)

![image](https://user-images.githubusercontent.com/64503158/125404132-eab0ec00-e3d3-11eb-850b-b640b32f56fc.png)

![image](https://user-images.githubusercontent.com/64503158/125404173-f8667180-e3d3-11eb-87b5-ae83022f853a.png)
