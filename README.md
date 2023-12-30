# 2023 Charged Up Picklist Code
The code goes through all the data and calculates the average score of cones per team and ranks them based on that. It then prints the processed data onto a seperate google sheet for the picklist. 

****Libraries**:**
- **Numpy** - not used throughout code, but imported
- **Pandas** - used for main data processing
- **Gspread** - used to access google sheet for picklist & raw data
- **Google.auth** - grabs credentials from google account
- **Google.colab** - helps grab credentials

# Automatic Sheet Code
This code is used to create a seperate sheet within the main spreadsheet for each team by copying a template page and renaming it based on the team number. It also changes the filter for team specific data to ensure that data is from the team on that page.

_**If you have any questions, let me know!!
**_
