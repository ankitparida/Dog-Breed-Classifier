[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

This project uses Convolutional Neural Networks (CNNs)! A convolutional neural network (CNN) is a type of artificial neural network used in image recognition and processing that is specifically designed to process pixel data. Here, we will learn how to build a pipeline to process real-world, user-supplied images.

![Sample Output][image1]

 The major objective is to understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer. 
The goal is to classify images of dogs according to their breed. Given an image of a dog, the algorithm will identify an estimate of the canine's breed. If supplied an image of a human, the code will identify the resembling dog breed.

## Project Workflow

Step 0: Import Datasets

Step 1: Detect Humans

Step 2: Detect Dogs

Step 3: Create a CNN to Classify Dog Breeds (from Scratch)

Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)

Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning)

Step 6: Write your Algorithm

Step 7: Test Your Algorithm

## Important File Descriptions

**dog_app.ipynb: ***Python File Containing the code required to build the CNN Model***

**extract_bottleneck_features.py: ***Function to extract bottleneck Features***

**images: ***Directory Containing Sample Images***

## Dataset & Bottleneck Features Used

Please refer to the below link to download the dataset required for this project:

1. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.

2. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder.

3. Download the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  Place it in the repo, at location `path/to/dog-project/bottleneck_features`.

4. For other reference files:  Clone the repository and navigate to the downloaded folder.
```	
git clone https://github.com/udacity/dog-project.git
cd dog-project
```

## Libraries Used
1. sklearn
2. keras
3. numpy
4. glob
5. matplotlib
6. Ipython
7. PIL
8. tqdm
9. cv2

## Results
Below are the test accuracy of the models which we have built in this Project:

CNN to Classify Dog Breeds (From Scratch): 1.4354%

CNN to Classify Dog Breeds (Using VGG-16): 45.5742%

CNN from Resnet50: 81.1005%

## Acknowledgements
I would like to give credit to:
* ![Udacity](https://classroom.udacity.com/nanodegrees/nd025)
* ![MachineLearning_Mastery](https://machinelearningmastery.com/evaluate-performance-deep-learning-models-keras/)
* ![AnalyticsVidhya](https://www.analyticsvidhya.com/blog/2021/08/developing-an-image-classification-model-using-cnn/)

# Github Link: [https://github.com/ankitparida/Dog-Breed-Classifier](https://github.com/ankitparida/Dog-Breed-Classifier/)
# Medium Blog Post Link: [https://medium.com/@ankitparida/dog-breed-classifier-using-cnn-5fcb4a37479b](https://medium.com/@ankitparida/dog-breed-classifier-using-cnn-5fcb4a37479b)
