# INDIAN SIGN LANGUAGE PREDICITON USING DEEP LEARING AND CNN
Using CNN and transfer learning to Correctly recognize the Indian sign languages

<strong>Number of classes</strong> : 32

# MODELS USED

## DEEP CNN MODEL
As a part of this project, I have used two models a deep cnn model given by the following architecture - :

![image](https://github.com/HariSkr11/indian-sign-language-detection/assets/98250904/402b5525-82b6-46c2-b132-407f94a54a87)



## TRANSFER LEARNING MODEL 

For the same purpose, I have used the VGG16 model which I directly exported from tensorflow using the stored weights of Imagenet

![image](https://github.com/HariSkr11/indian-sign-language-detection/assets/98250904/46483bee-9171-4f5b-a405-4de9531d9919)



The above image is the architecture of VGG16 model that has been used in the project. 

As part of transfer learning I have added an Input layer to input the images and 4 dense layers of neurons 512, 256, 128 and 64 respectively with dropout for regularization and to reduce overfitting.

![image](https://github.com/HariSkr11/indian-sign-language-detection/assets/98250904/32e11031-e2b7-4fe3-8416-ae217628fcea)





## RESULTS

Accuracy of Deep CNN model : <strong>75</strong>

The transfer model was able to give me an accuracy of <strong>85.53</strong>

The perfomance analysis plot is given below

![image](https://github.com/HariSkr11/indian-sign-language-detection/assets/98250904/54b0a52c-8f0e-4e37-8cac-602823745680)

