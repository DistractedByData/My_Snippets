# Pandas Dataframe Functions and Methods:

### i. Modify the number of columns displayed when printing a Dataframe:
#### Example 
```python
pd.set_option('display.max_columns',150)
```

Syntax: 
```python
pandas.set_option(pat, value)
```

Parameters:
- pat (`str`): Regexp which should match a single option. Note: partial matches are supported for convenience, but unless you use the full option name (e.g. x.y.z.option_name), \
  your code may break in future versions if new options with similar names are introduced.
- value (`object`): New value of option.

##### Pandas [Documentation](https://pandas.pydata.org/docs/reference/api/pandas.set_option.html)
---

### ii. Update the column labels of a DataFrame:
#### Example 
```python
df.columns = ['new_label1', 'new_label2', 'new_label3']
```

Syntax: 
```python
dataframe.columns = [list of new column labels]
```

Parameters:
- dataframe: The DataFrame object whose column labels you wish to update.
- [list of new column labels]: A list containing the new column labels. The length of the list should match the number of columns in the dataframe.

##### Pandas [Documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html)
---




