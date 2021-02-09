# ProblemFormulation
Most of existing house price estimation systems rely only on textual data like its neighborhood area and the number of rooms. In this project, we practice with TensorFlow Functional API to extract visual features from house photos and combining them with the house’s textual information.
The goal of this project is to build a novel house price estimation system by using both textual and visual inputs, other than only using textual information such as area, neighborhood, and number of bedrooms.
Build the best deep learning model and then show its RMSE and lift chart on test data.

# Dataset
https://github.com/emanhamed/Houses-dataset
This dataset contains both visual and textual information.
• Each house is represented by four images for bedroom, bathroom, kitchen and a frontal image of the house.
• The dataset folder contains 2140 images, 4 images for each house.
The dataset has a text file that contains the textual metadata of the dataset. Each row in the file represents the number of house in order. The numbers represent number of bedrooms, number of bathrooms, area of the house, zipcode and the price.


# Model Design
We are using TensorFlow Functional API. For each house, create a combined image using the 4 house images (bedroom, bathroom, frontal and kitchen). 

 
