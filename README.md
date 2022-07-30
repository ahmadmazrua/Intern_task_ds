# Intern_task_ds
## Data Science task:
	1. Import dataset
	2. Data preparation
		-Remove duplicates
		-Fill null values
		-Drop unnecessary Columns
	3. Data Visualisations: Using plots to answers this questions
		-Q1. Which drink has the highest calories from the dataset?
		-Q2. Highest Sugar Drink ?
    
  ### Reading a csv file into Dataframe .
  * It is the simplest form of storing data in tabular form as plain text. It is important to know to work with CSV because we mostly rely on CSV data in our day-to-day lives as data scientists.
  * Explore the dataset and find out the features.
  
  ### Remove duplicate rows.
  * Removing Duplicates in the context of data quality and then remove instances where there is more than one record of a of the same instance.
  * Our data has no duplication.
  
  ### Fill null values.
  * Our data has one column that contains the null value, and since this column is not among our interests, we did not fill it in
  
  ### Choose the columns of interest.
  * Here we removed the columns that we do not need in answering the questions and we chose three important columns for the answer(Beverage, Calories, Sugars (g)).
  
  ### Sorting Beverage by Calories to find Highest value.
  * Here we created a variable and put a dataframe in it with the three columns and arranged them in descending order based on calories and we will do the same with sugar.
  
  ### Ploting Beverage with Calories that showing highest calories.
  * Here we have created a figure to show the highest calorie value for any drink and we will do the same with sugar
  ![Screenshot](https://github.com/ahmadmazrua/Intern_task_ds/blob/master/index.png)  ![Screenshot](https://github.com/ahmadmazrua/Intern_task_ds/blob/master/index0.png)
