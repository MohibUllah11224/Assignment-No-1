# Assignment-No-1



## Q NO1: Write a function called proportion_of_education which returns the proportion of children in the dataset who had a mother with the education levels equal to less than high school (<12), high school (12), more than high school but not a college graduate (>12) and college degree.
Ans: first we will create a function that will read the cvs file  containing data on children's health and returns a dictionary with the proportion of children with different levels of education in their household. By using the command 'pd.read_csv()' Then The function calculates the proportion of children in the dataset with each level of education by calling the 'value_counts()' which counts the number of occurrences of each unique value in the column and returns a pandas Series object with the counts. The normalize=True parameter is used to convert the counts to proportions, so that the sum of all proportions is 1.
The resulting proportions are stored in a dictionary called EDUC1_dict, with education levels as keys and proportion as values.The function returns the EDUC1_dict dictionary.The assertions at the end of the code test that the function returns a dictionary with four items, where the keys are the expected education levels and the values are the expected proportions. The assertions also test that the function returns a dictionary object of the expected type.
