# Cuisine-Camouflage-Classifying-Meal-Origins

Welcome to "Cuisine Camouflage," a repository where machine learning meets culinary art. Utilizing the MLEnd Yummy Dataset, this project features two classifiers aimed at enhancing food image classification. The Basic Classifier identifies whether images contain rice or chips, honing in on subtle differences in texture and shape. The Advanced Classifier determines if dishes are homemade or restaurant-prepared, focusing on discerning the fine details of food presentation. These models illustrate the application of advanced image classification techniques in understanding and analyzing culinary aesthetics, providing tools for users to replicate results and explore further in the field of gastronomy.

Overview

This repository hosts two machine learning models leveraging the MLEnd Yummy Dataset for classifying dish images. The primary goal is to utilize advanced image classification techniques to predict key characteristics of dishes, aiming to distinguish between basic ingredients and determine the origin of the dish—whether homemade or restaurant-made. These models address distinct challenges in visual food recognition, providing insights into both culinary presentation and ingredient identification.
Problem Formulation

Basic Classifier

Machine Learning Problem: Build a classifier that differentiates images of dishes containing either rice or chips.
Interest Point: The ability to distinguish between rice and chips, despite their similar coloration, showcases the model's sensitivity to subtle textural and shape differences, which is critical in real-world food classification tasks.
Advanced Classifier
Machine Learning Problem: Develop a classifier to predict whether a dish in an image is homemade or restaurant-made.
Interest Point: This model explores the nuances of food presentation, highlighting how homemade dishes can often mirror the aesthetic appeal of restaurant dishes, challenging the classifier to discern fine details beyond mere appearance.
Results
Basic Model: Demonstrates robust performance with a marked accuracy in identifying chips, pointing to possible dataset biases.
Advanced Model: Excels in recognizing homemade dishes, possibly due to training data characteristics, while still delivering reliable predictions for restaurant-made dishes.
Conclusions
Basic Classifier: Needs further refinement or data adjustment to enhance accuracy in rice identification.
Advanced Classifier: Despite data imbalances, shows strong potential in generalizing across different types of dish presentations.
Repository Structure
basic_classifier.ipynb: Jupyter notebook for the basic classification tasks.
advanced_classifier.ipynb: Jupyter notebook for the advanced classification tasks.
data/: Dataset directory.
models/: Saved models directory.
docs/: Documentation and additional resources.
