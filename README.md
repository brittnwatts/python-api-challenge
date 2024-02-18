# python-api-challenge

This ReadMe serves to:
   1. Certify that this work is my own,
   2. Specify code source and its location in my 'python-api-challenge' repository,
   3. Clarify the reason for the assignment,

1. 
My name is Brittney Watts, and I am in the UNCC/EdX Data Analytics Bootcamp. Currently, we 
are working on Module 6 of our exploration into APIs and Geomapping using Python and Jupyter Notebook.

2. 
The source code is my interpretation of the information we have learned in class with some debugging help from forums and tutors, and here is a breakdown of the locations of each element of my assignment:

   python-api-challenge
    output_data
        cities.csv
        Fig1.png
        Fig2.png
        Fig3.png
        Fig4.png
    VacationPy
        VacationPy.ipynb
        vacationpy_api_keys.py
    WeatherPy
        WeatherPy.ipynb
        weatherpy_api_keys.py
    README.md

3. 
This assignment serves to track my understanding of GeoViews, Data Visualization with Matplotlib, API Requests, and the Python Language.

Python API Challenge:
   My task was to read in data from an Open Weather API and manipulate dataframes to draw conclusions on the weather for different coordinates. This API contains weather data for every set of coordinates in the world, and we can take all the data for a certain range to analyze the data based on location, timeframes, and hourly forecasts.
   
   My Steps: 
      - First, I was to create graphs to show the relationship between latitude v. temerature, humidity, cloudiness, and wind speed for the range of coordinates I desired. 
      - Split the dataset into separate Hemispheres. 
      - Compute a linear regression for every relationship in both the Northern and Southern Hemispheres. 
      - Analyze the data and make conclusions.
      - Take the dataframe for the data we retrieved and filter it based on ideal weather conditions.
      - Take these conditions and enter them into the GeoApify API request so that we can retrieve 'places' data for every city.
      - The last step was to create maps that visualized the Hotel Data for every location with ideal weather conditions!
      
Thank you!