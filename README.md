# python-api-challenge

This ReadMe serves to:
   1. Certify that this work is my own,
   2. Specify code source and its location in my 'matplotlib-challenge' repository,
   3. Clarify the reason for the assignment,

1. 
My name is Brittney Watts, and I am in the UNCC/EdX Data Analytics Bootcamp. Currently, we 
are working on Module 4 of our exploration into Matplotlib and Pandas using Python and Jupyter Notebook.

2. 
The source code is my interpretation of the information we have learned in class with some debugging help from forums and tutors, and here is a breakdown of the locations of each element of my assignment:

   matplotlib-challenge
    Pynaceuticals
        main.ipynb (my code)
    Resources
        Mouse_metadata.csv
        Study_results.csv
    README.md

3. 
This assignment serves to track my understanding of Pandas, Matplotlib, Jupyter Notebook, and the Python Language.

Pymaceuticals:
   My task was to read the data from the csv files and perform operations on them to analyze the effects of treatments for tumors on mice.
   The Mouse_metadata.csv file gives us general information and independent variables on the mice like their ids, their weight, and ages. The Study_results.csv file gives us performance data to analyze the results of different drugs on the mice.
   
   My Steps: 
      - First, I was to merge both csv files into a dataframe and find the number of mice of mice and any duplicates. After finding them, I was to clean the data by removing the duplicates and creating a new dataframe without duplicates.
      - Generate the mean, median, variance, standard deviation, and standard error of tumor volumes for each drug regimen and then put this information into a new dataframe of summary statistics. 
      - Create a dataframe that shows the final tumor volume of each mouse across the four treatments Capomulin, Ramicane, Infubinol, and Ceftamin. Then I was to calculate the quartiles, IQR, determine if there are any outliers, and populate a box plot that shows the distribution of fimal tumor volumes. 
      - Find a single mouse treated with Capomulin and generate a line plot that shows the tumor volume over time using timepoints.
      - Generate a scatter plot of mouse weight versus average observed tumor volume for the Capomulin treatment regimen. 
      - Calculate the correlation coefficient and linear regression model between mouse weight and tumor volume for the Capomulin treatment regimen, and plot the linear regression model.
      - The last step is to summarize my data and make a few conclusions which you can find at the very beginning of my source code!!!
      
Thank you!