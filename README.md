# Amazon-SentimentAnalysis

The program consists of several main parts:

1. Data processing
...The data is sorted by the 'wilson_lower_bound' column and the _'Unnamed: 0'_ column is removed from the dataframe.
2. Missing values analysis
...The '''python missing_values_analysis()'''' function is used to check the number and percentage of missing values for each column in the dataframe.
3. Dataframe checking
...The '''python check_dataFrame()''' function is used to check the dataframe shape (rows and columns), data type, missing values, duplicate values, and simple statistics (0%, 5%, 95%, 99%, and 100% percentiles).
4. Category class analysis
...The '''python check_class()''' function is used to check the number of classes of each column in the dataframe.
5. Data visualization
...The '''python categorical_variable_summary()''' function is used to display data visualizations such as counterplots and percentages of certain categories of variables. Visualizations are created using the plotly library and presented in the form of subplots.
6. Sentiment analysis
...The program uses _SentimentIntensityAnalyzer from nltk.sentiment.vader_ and _TextBlob_ to analyze the sentiment of the acquired data.

Overall, the program is used to check basic information about the data and analyze the sentiment of the data obtained from amazon. The program also displays data visualizations that are useful for understanding the data distribution and categories present in the dataframe.
