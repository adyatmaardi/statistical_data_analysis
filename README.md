# Statistical Data Analysis - Descriptive & Inferential Statistics

### Data Analyst Projects #2

##### Author : Achmad Adyatma Ardi
##### Email : achmad541997@gmail.com
##### IG : [@adyatmaardi](https://www.instagram.com/adyatmaardi/?hl=id)

## Prerequisites
1. Install necessary Python-module
  - [statistics](https://pypi.org/project/statistics/) (built-in) module - used to calculate mathematical statistics of numeric data.

           pip install statistics

   - [math](https://pypi.org/project/python-math/) module - Used to perform various mathematical calculations, such as numeric, trigonometric, logarithmic, and exponential calculations
   
           pip install python-math
   
   
   - [numpy](https://numpy.org/install/) module - used to perform a wide variety of mathematical operations on arrays

           pip install numpy

   - [pandas](https://pandas.pydata.org/docs/getting_started/install.html) module - It provides ready to use high - performance data structures and data analysis tools. It runs on top of NumPy and it is popularly used for data science and data analytics

           pip install pandas

   - [matplotlib](https://matplotlib.org/stable/users/installing/index.html) module - used to create 2D graphs and plots by using python scripts

           python -m pip install -U matplotlib
           
   - [seaborn](https://pypi.org/project/seaborn/) module - used to visualize data and exploratory data analysis

           pip install seaborn
           
   - [scipy](https://numpy.org/install/) module - used to solve scientific and mathematical problems

           pip install seaborn
           
   - [from IPython.display Import Image](https://ipython.org/install.html) module - used to load images from files, and to create new images

           pip install ipython
           
   - [warnings](https://pypi.org/project/pytest-warnings/) module - used to issue warning messages

           pip install pytest-warnings
           
## Data preparation
1. NumPy array
    - speed 
        - data : 99, 86, 87, 88, 111, 86, 103, 87, 94, 78, 77, 85, 86
        - nobs : 13
        - datatype : int
    - age
        - data : 5, 31, 43, 48, 50, 41, 7, 11, 15, 39, 80, 82, 32, 2, 8, 6, 25, 36, 27, 61, 31
        - nobs : 21
        - datatype : int
2. Pandas DataFrame
    - cars dataset
        - columns : 'Car', 'model', 'Volume', 'Weight', 'CO2'
        - nobs : 36 
        - datatype :
            1) 'Car' : str
            2) 'Model' : str
            3) 'Volume' : int
            4) 'Weight' : int
            5) 'CO2' : int
    - health dataset
        - columns : 'Duration', 'Average_Pulse', 'Max_Pulse', 'Calorie_Burnage', 'Hours_Work', 'Hours_Sleep'
        - nobs : 163
        - datatype :
            1) 'Duration' : int
            2) 'Average_Pulse' : int
            3) 'Max_Pulse' : int
            4) 'Calorie_Burnage' : int
            5) 'Hours_Work' : float
            6) 'Hours_Sleep' : float

## Objectives
1. Descriptive statistics
    - Measure of central tendency from NumPy Array and Pandas DataFrame
        1) Mean
        2) Median
        3) Mode
    - Measure of variability from NumPy Array and Pandas DataFrame
        1) Min, max and range
        2) Percentiles
        3) Variance
        4) Standard deviation
        5) Distribution
        6) Skewness
        7) Kurtosis
    - Summarize using describe method
2. Inferental statistics
    - Correlation between pairs of data
        1) Covariance matrix
        2) Correlation matrix
        3) Heatmap
        4) Correlation coefficient (CC)
            - Perfect linear relationship (CC = 1)
            - Perfect negative linear relationship (CC = -1)
            - No linear relationship (CC = 0)
    - Perform simple linear regression analysis
        1) Data preparation (extract and rename data from existing Pandas DataFrame)
        2) Plot the given data points
        3) Add needed columns (x-x̄), (y-ȳ), (x-x̄)*(y-ȳ), (x-x̄)^2, (y-ȳ)^2
        4) Sum up (x-x̄)*(y-ȳ), (x-x̄)^2, (y-ȳ)^2 columns 
        5) Calculate Pearson's correlation coefficient (r)
        6) Calculate standard deviation of X and Y variables
        7) Calculate slope (b)
        8) Calculate intercept (a)
        9) Plot the given data points and fit the regression line
        10) Predict value

capture :
[gdrive](https://drive.google.com/drive/folders/126drWOSN5SOEH3nN7CAvHNp3tr75GqgN)

