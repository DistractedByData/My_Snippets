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


