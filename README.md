# DataScience_Kmeans_OLS

Exercise 1
  Read the entire dataset: auto-mpg.csv as a DataFrame and print the numbers of rows and
  columns. Find in the dataset all the entries with a ? and replace them with a np.nan. Drop all
  rows that do not contain a value. Print again the numbers of rows and columns in the DataFrame
  
Exercise 2
  In continuation of Ex. 1, assign the columns weight and mpg into x and y numpy arrays,
  respectively. Perform Linear Regression using the Ordinary Least Squares method (you can use
  built-in functions, if you wish). Make predictions for the values: 1500 to 5000 with a step of 500,
  that is, 8 x-values. Plot the data points along with the regression line and the predicted values,
  and print: slope, y-intercept, r, using f-strings, on the plot title, as shown in the first Figure in the
  next page.
  
Exercise 3
  Read the entire dataset: housing.csv and perform K-means clustering, where K=6, on columns
  Longitude, Latitude which correspond to x, y, respectively. Plot the clusters as shown in the second
  Figure in the next page
