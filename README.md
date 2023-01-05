# Fake_Depth_estimation
we present a method for categorizing images based on the associated depth map. Our approach uses a convolutional neural network (CNN) trained on a large dataset of images and depth maps to classify images into different categories based on the depth information
In this study, we explored the use of machine learning techniques to classify images as real or fake based on their associated depth maps. We used a publicly available data set of [DESCRIBE DATA SET], which consists of 160 images with associated depth maps. The images in the data set are labeled as either real or fake.
After reviewing different review papers and analyzing our problem statement we decided to follow the current methodology depicted in the flowchart below.
Input: An image to be classified and its associated depth map.( using dataset of real and fake )
Preprocessing: Normalize the depth map and resize the image and depth map to the required dimensions(Feature normalization)
Feature extraction: Extract features from the image and depth map using a CNN.
Classification: Use the extracted features to classify the image into a specific category using a classifier.
Output: The predicted category for the input image.
