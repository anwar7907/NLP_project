# Natural Language Processing Project

For this project I will classify Yelp Reviews into 1 star or 5 star categories.  

# Columns    
Column Name | Description
------------ | -------------
date | The date of the review happened.
stars	 | The number of stars (1 through 5) assigned by the reviewer to the business.
text | The review text.
type | The type of the text.
cool | How much cool is the business (1 through 5).
useful | How much useful is the business (1 through 5).
funny | How much funny is the business (1 through 5).

# Summary of the solution:
## 1. Data overview:
   1. Data type
   2. Number of columns
   3. Numbers of rows
   4. Data description and statistical summary
       * The mean values of the numerical columns.
       * The correlation between the mean of the numerical columns
## 2. Data Analysis Exploration (EDA)
   1. Created 5 histgrams of text length based off of the star ratings
   2. Created a boxplot of text length for each star category 
   3. Created a countplot of the number of occurrences for each type of star rating
   4. Create a heatmap based off the correlation between the mean of the numerical columns
## 3. Setting up the data for machine learning
   1. Features engineering
       * Count how many character in the review text.
       * Created a dataframe that contains the columns of yelp dataframe but for only the 1 or 5 star reviews.
       * Created a CountVectorizer object.
   2. Data train test split
       * Sklearn.cross_validation
   3. Model train
       * Natural Language Processing model
         * MultinomialNB
## 4. Model predection
## 5. Model evaluations
   * Classification_report
   * Confusion_matrix
