# Meme-Analysis-Classification
Multi-Modal vs Multi Modal Classification - Neural Networks - using PyTorch - Memotional Dataset

I have classified Memes using neural networks working with PyTorch. 
First of all, 

Resizing Images:
I have resized all the images at an average size standard for all the images in the dataset. 

Extracting Image Features:
Then extracted image features using canny and Sobel filters. 
Dropped all the outliers that can affect the dataset distribution. 

Augmentation of Dataset: 
As the memotional dataset (meme images dataset) is not balanced and distributed among three classes: 1. neutral 2. positive 3. negative. 
To solve the issue we have done image augmentation and have generated new images to balance the class distribution.

Text Feature Extracting:
Secondly, I have extracted text from all the images and for extracting text features I have used glove.6b.

NEURAL NETWORK MODEL
PART I --> Multi Modal Neural Network Modal:
In this Model, in beginning each image and its respective text is sent through two separate Neural Networks adding multiple
layers and at some point I have concatenated both of them to a single Neural Network. 

PART II --> Multi Label Neural Network:
In this Model, in beginning each image and its respective text is sent through two separate Neural Networks adding multiple
layers but in the end after concatenation we have added multiple layers to that part of neural network as well 
leading to single output layer.

