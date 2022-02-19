# India-Cencus-2011-Data-Analysis-Project
The data is about total Population, Demography, Literacy, Districts, States, Workers, Religion, Education, Age.  The data used here is of 2011 India cencus of each district.  This data is available as a CSV file, downloaded from Kaggle.  We will analyze this dataset using the Pandas DataFrame.  Here, random sets of questions and instructions are given as an example for the practice &amp; learning purpose.



------------------------------------------------------
In this project, India Census 2011 data is analyzed in a very Easy To Understand (ETU) language.
Here, you will learn about the python commands & how to work on a real project of Data Analysis with Python. 
Questions are given in the project and then solved with the help of Python commands.

-----------------------------------------------------------------------

The commands that we used in this project :

* import pandas as pd -- To import Pandas library


* pd.read_csv - To import the CSV file in Jupyter notebook.


style.hide_index( ) - To hide the index of the dataframe.


style.set_caption('Description of the dataframe') - To give a caption to the dataframe.


isin( ) - To show all records including particular elements.


groupby(‘Col_1’)[‘Col_2’] .sum( )[‘value’] - GroupBy – Two Keys – Apply on Col_2 grouped by Col_1.


df[df.Col_1 == 'Element1']['Col_2'] - Filtering - Filter the records of the dataframe wrt to Element1 of Col1 and then showing results of Col2 only.


set_index( ‘Col_Name’ ) - To set any column of a DF as an index.


add_prefix(‘value_’) - To add prefix to the column name.


add_suffix(‘_value’) - To add suffix to the column name.



-----------------------------------------------------------------------------------

Q. 1) How will you hide the indexes of the dataframe.


Q. 2) How can we set the caption / heading on the dataframe.


Q. 3) Show the records related with the districts - New Delhi , Lucknow , Jaipur.


Q. 4) Calculate state-wise :

A. Total number of population.

B. Total no. of the population with different religions.


Q. 5) How many Male Workers were there in Maharashtra state ?


Q. 6) How to set a column as index of the dataframe ?

Q. 7a) Add a Suffix to the column names.

Q. 7b) Add a Prefix to the column names.



------------------------------------------------------
