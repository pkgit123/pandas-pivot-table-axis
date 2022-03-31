# pandas-pivot-table-axis
Rename the axis in a pivot table

```
df = pd.pivot_table(df,index="CNTRY",columns="TYPE", values='VALUE') \
       .reset_index().rename_axis(None, axis=1)
```

In particular, look at the method `.rename_axis(None, axis=1)`
 

### Reference:
* https://stackoverflow.com/questions/44513488/how-to-remove-multilevel-index-in-pandas-pivot-table
