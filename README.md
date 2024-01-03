# My_Projects
<br>
Machine Learning Projects
(1)Movie Recomendation System:
In this  Project we use <b>content based recommendation system</b>

The following steps are taken to build this project :

1.Data collection : The Data is collected from Kaggle 
2.Data Preprocessing :  	
  	In this step we have merged the data frame based on title column and then 
	  Then removed the unwanted columns by checking the missing data and since only 3 rows in the overview columns we found and can’t be        
	  replace with the relevant values we drop those 3 rows. 
    Then we check for duplicate values .
	  The few columns have string data which is converted into a list.
	  We add a tags column in the data frame by concatenating  overview , genres , keywords , cast, crew 	columns.
3. Convert the given text to vectors 
4.Use cosine similarity to calculate the distance


(2)Stress Predict 
In this project the data preprocessing steps were applied to the dataset and two classifiers namely Decision tree and Random forest are used to predict if the individual has stress or not and a detailed comparison is done to find the best model to solve this problem.
