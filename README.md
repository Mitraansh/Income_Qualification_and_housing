# Income_Qualification_and_housing 

DESCRIPTION

Identify the level of income qualification needed for the families in Latin America

# Problem Statement Scenario:
Many social programs have a hard time making sure the right people are given enough aid. 
It's tricky when a program focuses on the poorest segment of the population. 
This segment of population can't provide the necessary income and expense records to prove that they qualify.

In Latin America, a popular method called Proxy Means Test (PMT) uses an algorithm to verify income qualification. 
With PMT, agencies use a model that considers a family's observable household attributes like the material of their 
walls and ceiling or the assets found in their homes to classify them and predict their level of need. 
While this is an improvement, accuracy remains a problem as the regions population grows and poverty declines.

The Inter-American Development Bank (IDB) believes that new methods beyond traditional econometrics, 
based on a dataset of Costa Rican household characteristics, might help improve PMT's performance.

# Following actions performed:
•	Understand the type of data.
•	Write a function print_various_data_info with input parameter as DataFrame. This function will print various info of DataFrame (How many entries, how many columns, column name(s), how many nont null columns for each column, DataType of each column, Shape of data, Null count for each columns.
•	Print the first 10 rows. Print the last 10 rows,
•	Write a function print_numerical_columns with input parameter as DataFrame to print numerical columns (Int/Float). Return column list.
•	Write a function get_int_float_dtype_null_column_list
with input parameter as DataFrame to print numerical columns (Int/Float) containing Null value. Return column list.
•	Write a function fill_int_float_dtype_null_cells_data_with_mean with parameters as DataFrame and column_list to fill Null cells of int_or_float column(s) with mean() value of the corresponding column.   
•	Checking if there any Duplicate rows
•	Write a function get_object_dtype_column_list with parametsr as DataFrame to get the list of all Object Dtype Column(s). Return column list. 
•	Note: This is the only place  you have to use House Pricing Data file. Rest of the places you use Income Qualification data. >>> Analyzing the value_count of various types of 'ocean_proximity' to see if it has limited set of data for encoding purpose
•	Write a function get_category_column_list with parameters as DataFrame and object_column_list to get Object Dtype categorical column(s) having <= 10 diff type of data. Return category_column_listand category_column_value_list. Second one is list of list.
•	Write a function apply_category_column_encoding with parameters as DataFrame, category_column_list, category_column_value_list and create additional columns and drop the original column. Additional column will contain 1 or 0 depending upon the corresponding column and categorical value. 
•	Check if there are any biases in your dataset.
•	Check whether all members of the house have the same poverty level.
•	Check if there is a house without a family head.
•	Set poverty level of the members and the head of the house within a family.
•	Remove null value rows of the target variable.
•	Marge the two DataSets 
