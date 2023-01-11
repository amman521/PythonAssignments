Q1. How do you load a CSV file into a Pandas DataFrame?
Answer-> import pandas as pd
df = pd.read_csv(r'Path where the CSV file is stored\File name.csv')
print(df)

Q2. How do you check the data type of a column in a Pandas DataFrame?
Answer-> using dtype attribute.

Q3. How do you select rows from a Pandas DataFrame based on a condition?
Answer->  Selecting rows using []

Q4. How do you rename columns in a Pandas DataFrame?
Answer-> data1 = {'Name':['Jai', 'Princi', 'Gaurav', 'Anuj'], 
        'Age':[27, 24, 22, 32], 
        'Address':['Nagpur', 'Kanpur', 'Allahabad', 'Kannuaj'], 
        'Qualification':['Msc', 'MA', 'MCA', 'Phd']} 
df.rename(columns={'Name':'UserName'},inplace=True)
df

Q5. How do you drop columns in a Pandas DataFrame?
Answer-> df.drop()

Q6. How do you find the unique values in a column of a Pandas DataFrame?
Answer->  unique()

Q7. How do you find the number of missing values in each column of a Pandas DataFrame?
Answer-> isnull()

Q8. How do you fill missing values in a Pandas DataFrame with a specific value?
Answer->  fillna()
Q9. How do you concatenate two Pandas DataFrames?
Answer->  concat()

Q10. How do you merge two Pandas DataFrames on a specific column?
Answer-> concat() or merge()

Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?
Answer-> aggregate()

Q12. How do you pivot a Pandas DataFrame?
Answer-> pivot()

Q13. How do you change the data type of a column in a Pandas DataFrame?
Answer-> astype()

Q14. How do you sort a Pandas DataFrame by a specific column?
Answer-> sort_values()

Q15. How do you create a copy of a Pandas DataFrame?
Answer-> copy()

Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?
Answer-> dataFrame = pd.DataFrame({'Name': [' RACHEL  ', ' MONICA  ', ' PHOEBE  ',
                                   '  ROSS    ', 'CHANDLER', ' JOEY '],
                          'Age': [30, 35, 37, 33, 34, 30], 
                          'Salary': [100000, 93000, 88000, 120000, 94000, 95000],
                          'JOB': ['DESIGNER', 'CHEF', 'MASUS', 'PALENTOLOGY',
                                  'IT', 'ARTIST']})
display(dataFrame.loc[(dataFrame['Salary']>=100000) & (dataFrame['Age']< 40) & (dataFrame['JOB'].str.startswith('D')),
                    ['Name','JOB']])

Q17. How do you calculate the mean of a column in a Pandas DataFrame?
Answer-> mean()

Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?
Answer-> std()

Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?
Answer-> corr()

Q20. How do you select specific columns in a DataFrame using their labels?
Answer-> use square brackets ['a']

Q21. How do you select specific rows in a DataFrame using their indexes?
Answer-> iloc[100]

Q22. How do you sort a DataFrame by a specific column?
Answer-> sort.values()

Q23. How do you create a new column in a DataFrame based on the values of another column?
Answer->  pd.DataFrame(
    [
        (1, 'Hello', 158, True, 12.8),
        (2, 'Hey', 567, False, 74.2),
        (3, 'Hi', 123, False, 1.1),
        (4, 'Howdy', 578, True, 45.8),
        (5, 'Hello', 418, True, 21.1),
        (6, 'Hi', 98, False, 98.1),
    ],
    columns=['colA', 'colB', 'colC', 'colD', 'colE']
)
print(df)

Q24. How do you remove duplicates from a DataFrame?
Answer-> drop_duplicates()

Q25. What is the difference between .loc and .iloc in Pandas?
Answer-> The main difference between loc and iloc is -> loc is label-based, which means that you have to specify rows and columns based on their row and column labels. iloc is integer position-based, so you have to specify rows and columns by their integer position values














