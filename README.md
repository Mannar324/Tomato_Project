# Tomato Recognition system
## Project OverView
- Build a Webapp that identifiy the disease of leaf of tomato to help farmers take a Preventive measures.
    ### How it Works:  
    1. **Upload Image:** Go to the **DiseaseRecognition** page and upload an image of a plant.
    2. **Analysis:** Our system will process the image using advanced algorithms to identify potential diseases.
    3. **Results:** View the results
       
## Resources Used

- language:python 
- libraries:pandas, numpy, sklearn,tensorflow ,matplotlib, seaborn,streamlit
to install the libraries use this command:

```bash


  pip install 'name of library'
```           

## Data Preprocessing
- for prepare images for Convolutional Neural Network (CNN) models, it is essential to resize and scale the images to ensure they are suitable for the model.

## Model Building
First, I transformed the Disease name Column to categorical using One Hot Encoding(OHE). I also split the data into train and tests sets with a test size of 20%.   
I used Pre-trained model EfficientNetB3.

## Model Evaluation
after evaluation the model achevied 
97% in Train Data ,Validation
and Test Data.

## Deployment 
In this step, I built a streamlit web app that was run on a local device, it upload image from user and returns predicted disease.


## ScreenShots
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights:

![alt text](https://github.com/Mannar324/Laptop_price_prediction/blob/main/EDA%20analysis/newplot.png "price distribution")
![alt text](https://github.com/Mannar324/Laptop_price_prediction/blob/main/EDA%20analysis/count%20category.png "Category Count")
![alt text](https://github.com/Mannar324/Laptop_price_prediction/blob/main/EDA%20analysis/pricebercat.png "price ber Category")

 
