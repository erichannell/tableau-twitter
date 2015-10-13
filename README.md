#####A script to pull tweets out of twitter and push them into a Tableau Data Extract (.tde) file.

Give it a term to search for and it will grab tweets as they fly by.

======

For each tweet this data will be captured:
* tweet text
* sentiment (using TextBlob to calculate a value between -1 and 1)
* username
* language of tweet
* country
* time stamp of tweet creation
* latitude and longitude (if available)
* platform used to send tweet from

Written by Eric Hannell

This is free and available for anyone to use and modify.