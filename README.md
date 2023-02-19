# Nigeria-Towns


### Overview
This program has the goal of taking a list of municipalities in Nigeria and outputting the state each one is located in. This is done by scraping the web with a given list of municipalities in Nigeria and creating an excel file documenting both the name of the municipality and the state it is located in. The selenium chrome webdriver is used to obtain search results from Google Maps, and state data is written to an excel file using xlwt.  This output excel file is in the repo as `municipalities_to_states_nigeria.xls`. Selenium and xlwt are required for it to be run.

#### Process
1. The list of municipalities is created the output excel sheet is initialized
2. Each municipality is searched in Google Maps.  The state location of any results in the target country (Nigeria) will be stored in a set (to prevent duplicates) and then written to the excel file.

#### Use case
I had a friend working on a Gov project who had an excel file of municipalities in Nigeria but needed the states they were in to continue with his research. I wanted to build a program to solve this problem in a fun way.  Unfortunately, before this program was up and running, my friend found a dataset online that he could use to find what he needed :sob: