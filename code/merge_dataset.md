```py
# Merge the two datasets based on the common attribute "index"
new_data = pd.merge(df1, df2, on='index')
print("New Merged Dataset:\n", new_data)
```
