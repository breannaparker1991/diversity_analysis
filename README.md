# Diversity Anlysis By Breanna Parker

Background/History: This project uses two datasets, one with employee information and one with the company hierchy. These were combined to make data analysis easier to see what columns are affecting someone's pay. 

Data Explanation (Data prep/Data dictionary/etc): both datasets were merged, and then a column was added to include everyone's "level" in the company (i.e. how many people work under them). Then another column was added to include the exact number of people they are in charge of. Outliers were then removed from this data. This was because there is only one CEO, which could highly skew the data, and only four other people were removed due to being an outlier. Multiple graphs were then made to visualize how different factors affected someone's pay. 

Methods: I created a preprocessor pipeline that handles missing values, MinMax scale numeric values, and one hot code categorical values. Used selectKbest to find the top 3 most influential columns. Then tried multiple models to see if I could accurately determine the pay range for new employees

Analysis: The data all looked great until I started running the models. I could not get a model to be above 14% r2 value with a MAE of 70k which is very inaccurate so none of the models I found could be used. This is my most complicated analysis project so I'll continue to work on it until I find what works best

Conclusion: This is a great project but still needs additional work
