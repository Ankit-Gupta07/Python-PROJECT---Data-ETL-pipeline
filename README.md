# Python-PROJECT---Data-ETL-pipeline
A jupyter notebook with simple explanations for all of the code. The code EXTRACTS raw data from various sources, TRANSFORMS it with every necessary step, and finally LOADs it to various destinations. It displays the whole process (with all the steps) of a critical skill - "data engineering".

# ETL: Extract, Transform, Load with Python
<br>Welcome to the repository ! This project showcases the entire process of "data ETL". Its main goal is to illustrate the ETL process through a Python-based implementation. The project is structured into three main sections: Extract, Transform, and Load. Each section performs its designated tasks -

i) **EXTRACT** - We first extract data from these sources - CSVs, APIs, JSONs, XMLs, Databases (SQLite & PostgreSQL) & store it in a pandas dataframe using Python libraries like pandas, requests, BeautifulSoup, sqlite3, and pyscopg2.

ii) **TRANSFORM** - Here we make the data more suitable for analysis by applying these steps on data - combine, clean, type conversion, handle missing & duplicate values, fitting a linear regression model, finding & removing outliers, feature scaling and engineering using Python libraries like numpy, pandas, pycountry, sklearn, and matplotlib.  

iii) **LOAD** - Lastly we store the transformed data into these destinations - CSVs, JSONs and Databases (SQLite & PostgreSQL) using Python libraries like pandas, sqlite, and pyscopg2

The end goal of the notebook is to combine these data sets together so that we can run a machine learning model predicting World Bank Project total costs or the GDP of a country as per their population or anything you want.

## Features
- **Index**: navigates the user to any particular step in the entire process
- **Code**: demonstrates each phase of the ETL process with explanatory comments to run the code
- **Markdown**: gives an easy understanding of the concepts used throughout the notebook
- **Viusalisation**: helps in understanding the spread of data and results of data transformations
- **Diagram**: focuses on understanding the process-flow of steps
- **Screenshots**: showcases different case-scenarios

## Files
- **kaggle/input** - a folder which contains all the datasets
- **DF to DB.csv** - a CSV file used to read the data into pandas df & then storing it in a PostgreSQL table
- **ETL_project.ipynb** - a Jupyter notebook which has everything in it - code + comments + markdowns for explanations
- **Video - preview.mp4** - a small gist of how the notebook looks like

## How to Use
1. Download the Python code: Clone or download the repository to your local machine.
2. Install Dependencies: Make sure you have all the required packages mentioned in the code installed in your environment.
3. Navigate to the Jupyter Notebook: Open the Jupyter Notebook (ETL_Project.ipynb) to access the code and explanations.
4. Execute the Code: Follow the step-by-step instructions provided in the notebook to perform the ETL process.
   
## Getting Started
To get started, clone this repository to your local machine and open the ipynb file. Start going through the notebook and execute the code using the explanations and comments given to perform ETL on raw data. 

## Contributions and Feedbacks
Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub repository. I appreciate your feedback and are committed to making this dashboard even better.
Happy analyzing!
