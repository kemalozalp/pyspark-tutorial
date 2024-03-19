# PySpark Tutorial
I created a Jupyter notebook to demonstrate simple PySpark commands on multiple .csv files. I strictly followed PySpark tutorial from FreeCodeCamp by Krish Naik.
I have made a few changes here and there which seemed more efficient to me from coding perspective, but my work is not original.

## How can this repo help you?
If you are coding in Python and familiar with the Pandas library, you can download the 'tutorial.ipynb' file and run cells to understand how you can do dataframe operations you do with Pandas using PySpark. 

In the tutorial.ipynb, I demonstrated:
1. Installing PySpark
2. Reading a .csv file using two different commands
3. Basic operations, such as
  - Getting column names
  - Slicing the dataframe
  - Getting summary statistics
  - Adding a column
  - Dropping a column
  - Renaming a column
4. Handling missing data
5. Filtering data
6. Grouping and aggregating data
7. Training a regression model using PySpark ML

More advanced applications of PySpark is underway. So, sit tight!

## How to start

I recommend creating a conda environment using the eny.yaml file. To do that:
1. Install anaconda on your device if you haven't have it already. To do that, follow the [link](https://www.anaconda.com/download){:target='_blank'}
2. Open a terminal window if you're using Mac OS or Linux, or a command window if you're using Windows and navigate to your working directory where you have the env.yaml file
3.```conda env create --prefix /<enter>/<your>/<path-to-env> -f env.yaml```
4. ```conda activate pyspark```
5. You should be able to run the command in the 'tutorial.ipynb' without any problem now.
