# CEO Dismissal Project

I found a dataset which contained a 'notes' column, indicating the circumstances for CEOs being dismissed from a business. I wondered if there were changes in the reported reasons over time, especially considering the rise of social media in recent years and the power of crowds to hold power to account.

I explored the data using Pandas Dataframes. However, to determine the most commonly reported words, I had to create a list of all the individual words from each report and do a value count after removing stopwords.

Once I found that retirement and resignation were the two most common reasons stated, I filtered the Dataframes for just the rows where these words were present, by using boolean values. I then expored these as CSV files.

Once in CSVs, I created the line graph to compare the continuous data over time to establish a trend.
 
