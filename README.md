# OpenFoodFacts-EDA
## Data tidying, cleaning, modelling and exploration of the OpenFoodFacts dataset.

This project is made as part of the exam for the Data Science 2018 [SoftUni](https://softuni.bg) course.

### Requirements
- The [Anaconda 3](https://anaconda.com) package or higher with Python v3.6.x or higher and Jupyter Notebook.

- The packages that come with Python 3, which include:

  - pandas - main library used for loading, cleaning and filtering the datasets
  - numpy - for math calculations, working with NaN's, filtering with conditions
  - matplotlib - for visualizations during exploration
  - nose.tools - for unit testing
  - scipy - for hypothesis testing
  - scikit-learn - preprocessing and logistic regression
  
- The Matplotlib [Basemap](https://matplotlib.org/basemap/) Toolkit - for map plotting

### Usage 
Download **version 5** of the [Open Food Facts](https://www.kaggle.com/openfoodfacts/world-food-facts/version/5) dataset and place it in the 'data/' folder alongside the other datasets. This is the dataset version that I worked on, other versions don't guarantee reproducibility and some tests will most likely fail.

### Idea behind the exploration
In an attempt to research the nutrition values of the french products and what affects them, I have chosen to compare them to fast-food products such as McDonalds - in terms of meat quality, and Starbucks - in terms of beverage quality. I will also be looking into other factors such as packaging, food additive count and whether the products contain ingredients with palm oil or not. So the main questions I'll be looking to answer are:

   1. Which nutrient has the biggest impact on the nutrition grade?

   2. How do french meat and beverages compare to McDonalds meat and Starbucks beverages in terms of nutrients?

   3. Do other factors like food packaging, additive count and palm oil in the ingredients have an impact on the nutrition value?

To answer these questions I have chosen to single out the three most popular and most essential nutrients contained in food: carbohydrates, fat and protein.

### Project structure
I have chosen to divide my project in three separate notebooks, in order to improve readability. The first part involves obtaining and cleaning the three datasets, as well as filtering them for EDA and finally exporting them. The second part is the core of the project and includes exploratory data analysis on the three cleaned datasets, visualizations and hypothesis testing. The final part is done just for fun - a simple logistic regression model, which will attempt to predict whether a french product contains additives or not.

