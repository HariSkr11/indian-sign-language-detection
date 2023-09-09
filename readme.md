# INDIAN SIGN LANGUAGE PREDICITON USING DEEP LEARING AND CNN
Using CNN and transfer learning to Correctly recognize the Indian sign languages

<strong>Number of classes</strong> : 32

# MODELS USED

## DEEP CNN MODEL
As a part of this project, I have used two models a deep cnn model given by the following architecture - :

![image](https://github.com/HariSkr11/indian-sign-language-detection/assets/98250904/b89a9300-fe54-47fb-ac98-789dab2d9891)


## TRANSFER LEARNING MODEL 

For the same purpose, I have used the VGG16 model which I directly exported from tensorflow using the stored weights of Imagenet

![image](https://github.com/HariSkr11/indian-sign-language-detection/assets/98250904/3aef388d-09cb-4435-9cc2-62db324de67e)


The above image is the architecture of VGG16 model that has been used in the project. 

As part of transfer learning I have added an Input layer to input the images and 4 dense layers of neurons 512, 256, 128 and 64 respectively with dropout for regularization and to reduce overfitting.

![image](https://github.com/HariSkr11/indian-sign-language-detection/assets/98250904/8580aa4e-ec37-480e-ab4c-1923a87462b4)




## RESULTS

Accuracy of Deep CNN model : <strong>75</strong>

The transfer model was able to give me an accuracy of <strong>85.53</strong>

The perfomance analysis plot is given below

![image](https://github.com/HariSkr11/indian-sign-language-detection/assets/98250904/d6e38ed3-25bd-4541-babb-45e83ca1f878)
