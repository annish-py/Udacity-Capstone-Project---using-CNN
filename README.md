[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview



Welcome to the Convolutional Neural Networks (CNN) project in the AI Nanodegree! In this project, you will learn how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, your algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

Along with exploring state-of-the-art CNN models for classification, you will make important design decisions about the user experience for your app.  Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline.  Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.  Your imperfect solution will nonetheless create a fun user experience!

## Project Instructions

### Dependencies

1. Clone the repository and navigate to the downloaded folder.
```	
git clone https://github.com/udacity/dog-project.git
cd dog-project
```

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`. 

3. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

4. Donwload the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  Place it in the repo, at location `path/to/dog-project/bottleneck_features`.


## Detect Humans
Assess the Human Face Detector
The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected, human face.

## Detect Dogs
Use a pre-trained VGG16 Net to find the predicted class for a given image: `dog_detector` function returns `True` if a dog is detected in an image and `False` if not.

Assess the Dog Detector
The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected dog.

## CNN to Classify Dog Breeds from Scratch
CNN architecture of trained model attains at least **11%** accuracy  with **20 epochs** on the test set.

## Transfer Learning - CNN to Classify Dog Breeds  
Model architecture built with the  pre-trained model (**Resnet50**)

Accuracy has been achieved up to **81%** with **30 epochs**

You can find the medium blog post link [here](https://annishprashanth.medium.com/dog-breed-classifier-using-cnn-udacitys-capstone-project-32b6f3a1bfaf)

||||||| bc5a74e
=======
[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview



Welcome to the Convolutional Neural Networks (CNN) project in the AI Nanodegree! In this project, you will learn how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, your algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

Along with exploring state-of-the-art CNN models for classification, you will make important design decisions about the user experience for your app.  Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline.  Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.  Your imperfect solution will nonetheless create a fun user experience!

## Project Instructions

### Dependencies

1. Clone the repository and navigate to the downloaded folder.
```	
git clone https://github.com/udacity/dog-project.git
cd dog-project
```

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`. 

3. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

4. Donwload the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  Place it in the repo, at location `path/to/dog-project/bottleneck_features`.


## Detect Humans
Assess the Human Face Detector
The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected, human face.

## Detect Dogs
Use a pre-trained VGG16 Net to find the predicted class for a given image: `dog_detector` function returns `True` if a dog is detected in an image and `False` if not.

Assess the Dog Detector
The submission returns the percentage of the first 100 images in the dog and human face datasets that include a detected dog.

## CNN to Classify Dog Breeds from Scratch
CNN architecture of trained model attains at least **11%** accuracy  with **20 epochs** on the test set.

## Transfer Learning - CNN to Classify Dog Breeds  
Model architecture built with the  pre-trained model (**Resnet50**)

Accuracy has been achieved up to **81%** with **30 epochs**

You can find the link to the medium blog post below,

[Medium Blog Post](https://annishprashanth.medium.com/dog-breed-classifier-using-cnn-udacitys-capstone-project-32b6f3a1bfaf)
