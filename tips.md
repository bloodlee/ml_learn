# Summary

## Tips of data processing

+ Use **pd.read_csv()** to convert a CSV file into DataFrame (df)
+ Use **df.drop()** to drop the useless columns.
+ Use **df.info()** to check if there is any null values exist in DF.
+ NA values need to drop off or fill some values in, such as means values.
+ **"axis = 1"** means to index by columns, 0 means by rows.
+ Categorical values need to be replaced by values before training or predicting.