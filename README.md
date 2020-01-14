# Pandas-Practice

Contents

## Read write display a dataframe)
- pd.read_csv()
- pd.options.display.max_rows = 10
- pd.DataFrame({'col1':[1,2,3], 'col2':[1,2,3]})
- set_index
- rename_axis

## Basic data frame summary
- df.shape
- df.columns
- df.dropna(axis=0)
- df.describe()
- df.loc
- df.iloc
- df.count()
- df.head()

## Data Frame vs. Series

## Groupby
- hist()
- plot.bar()
[Reference](https://www.kaggle.com/learn-forum/60581)
- MultiIndex 
[Reference](https://jakevdp.github.io/PythonDataScienceHandbook/03.05-hierarchical-indexing.html)

## Merge

## Misc
- \[index for index in aa if aa>1\]
- a=\{x: function(x) for x in range\}, min(a,key=a.get)
- plot label rotation
[Reference](https://www.drawingfromdata.com/how-to-rotate-axis-labels-in-seaborn-and-matplotlib)
- datatime
-  scikit-learn library 
   - from sklearn.tree import DecisionTreeRegressor
   - model = DecisionTreeRegressor(random_state=1) 
   - model.fit(x,y)
   - model.predict(xxx)
   - from sklearn.metrics import mean_absolute_error
   - from sklearn.model_selection import train_test_split
- print format
   - print("blah: %d" %dataname)
   - print("blah: {:,.0f}".format(dataname))
