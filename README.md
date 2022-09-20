# Classifying Images of Sea Animals

**Project Description:** In this project, I build a convolutional neural network model to classify images of sea animals using the Tensorflow library. 

**Link to Project**: [Jupyter Notebook](https://github.com/johncarlomaula/sea-animal-classification/blob/main/image_classifier.ipynb)

## Main Goals:
- Prepare the image dataset for modeling
- Build a convolutional neural network model to classify images of sea animals
- Improve the model using various methods such as increasing complexity, data augmentation, and hyperparameter tuning

## Project Summary:

- The dataset contains a total of 11,742 images with 19 types of sea animals.
- My initial CNN model had a test accuracy of 37.1%, but by adding more layers and utilizing data augmentation, I was able to increase accuracy to 48.6%.
- The models generally performed well in classifying *turtles/tortoises*, *sea urchins*, *jellyfish*, *crabs*, and *starfish* with F1-scores ranging from 0.62 - 0.80. They performed badly in classifying *eels*, *octopus*, *puffers*, *sea rays*, and *squids* with F1-scores of 0.05 - 0.30.
- Possible reasons as to why the models have a fairly poor performance include having only a basic knowledge of CNN’s, insufficient training set, use of suboptimal tools, and lack of access to a high-performance computer. 

## Links:

These are the resources I used to help me complete this project.

1. https://www.kaggle.com/datasets/vencerlanz09/sea-animals-image-dataste
2. https://keras.io/about/
3. "Neural Networks Part 8: Image Classification with Convolutional Neural Networks (CNNs)." *YouTube*, uploaded by StatQuest with Josh Starmer, 8 March 2021, 
https://www.youtube.com/watch?v=HGwBXDKFk9I
4. "Loading in your own data - Deep Learning basics with Python, TensorFlow and Keras p.2." *YouTube*, uploaded by sentdex, 18 August 2018, https://www.youtube.com/watch?v=j-3vuBynnOE&t=268s
5. “Real-World Python Neural Nets Tutorial (Image Classification W/ CNN) | Tensorflow &amp; Keras.” *YouTube*, uploaded by Keith Gill, 8 June 2020, https://www.youtube.com/watch?v=44U8jJxaNp8. 
6. "Data augmentation to address overfitting | Deep Learning Tutorial 26 (Tensorflow, Keras & Python)." *YouTube*, uploaded by codebasics, 1 November 2020, https://www.youtube.com/watch?v=mTVf7BN7S8w
