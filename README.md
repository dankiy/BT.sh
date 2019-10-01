# BT.sh
bash script for downloading flight data from: https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236

Run downloader.sh downloads, unzips to csv in data folder
Then it removes unessesary commas. Displays header row, counts columns for comparison against expected number of 27 and gives a count of the observations (rows) in each file  

You can edit the for loops where the YEAR and MONTH variable iterates over a range to download back series over different dates.

By default these values are set to download data between 2013 and 2018 inclusive for all months.

Code adapted from examples shown in Chapter 2 of: 
“Data Science on the Google Cloud Platform by Valliappa Lakshmanan (O’Reilly). Copyright 2018 Google Inc., 978-1-491-97456-8.”
Please refer to that book for details of how the code works if unsure.

You can also visit the github repo for this chaper here: https://github.com/GoogleCloudPlatform/data-science-on-gcp/tree/master/02_ingest
