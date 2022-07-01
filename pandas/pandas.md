> July 1st. 2022
# About Pandas Datetime

## Make 'Year' columns
## from 'completed_at' column
> df['Year'] = df['completed_at'].dt.year

## Make 'Month' columns
## from 'completed_at' col
> df['Month'] = df['completed_at'].dt.month

## Make 'Day' col
## From 'completed_at' col
> df['Day'] = df['completed_at'].dt.day
