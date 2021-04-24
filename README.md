
## Project Overview

This is a Convolutional Neural Networks (CNN) project to detect dog breeds based on dog pictures! Given an image of a dog, the algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  



## Project Motivations

This is a good chance to explore CNN in object detection in pictures and try out different pre-trained layers that is trained in public datasets. By doing this project, we can understand the performance of different CNN architecture 



## Instructions

1. Clone the repository and navigate to the downloaded folder.
```	
git clone git@github.com:junfang219/Convolutional_Neural_Networks_Dog_Identification_App.git
```

2. Another option is to navigate to the dog_app.ipynb

   https://github.com/junfang219/Convolutional_Neural_Networks_Dog_Identification_App/blob/main/dog_app.ipynb


## Project Structure

We break the jupytor notebook into separate steps:

- Step 0: Import Datasets

- Step 1: Detect Humans

- Step 2: Detect Dogs

- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)

- Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)

- Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning)

- Step 6: Write your Algorithm

- Step 7: Test Your Algorithm

  The results are showing in the dog_app jupytor notebook file.



## Download Datasets and Bottleneck files

If you want to run this code on your local computer, you'll also need to download the following;

[Dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages.

[Human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). Unzip the folder and place it in the repo, at location path/to/dog-project/lfw. If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.

[VGG-16 bottleneck](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) features for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

[VGG-19 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG19Data.npz) for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

[ResNet-50 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogResnet50Data.npz) for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

[Inception bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogInceptionV3Data.npz) for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features.

[Xception bottleneck](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogXceptionData.npz) features for the dog dataset. Place it in the repo, at location path/to/dog-project/bottleneck_features



## Requirements

opencv-python==3.2.0.6
h5py==2.6.0
matplotlib==2.0.0
numpy==1.12.0
scipy==0.18.1
tqdm==4.11.2
keras==2.0.2
scikit-learn==0.18.1
pillow==4.0.0
ipykernel==4.6.1
tensorflow==1.0.0

## Result summary

**Model. Accuracy**

CNN from scratch = 7.89%

CNN with VGG16 = 38.8%

CNN with Resnet50 = 81.58%

## Blog Post

I post a post on Medium, check out [here](https://junfang219.medium.com/convolutional-neural-networks-write-an-algorithm-for-a-dog-identification-app-5cea27d3e1eb)

