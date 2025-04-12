Journal
Short description: Journal.py is an application that semi-automates journaling in MS Word.
Prerequisites: To run Journal.py, you need the following prerequisites:
● Python 2.6 or greater.
● The pip package management tool
● Test account for the Google Drive API ‘DAVPJournal’
Login: davp.journal.api.test@gmail.com Password: DAVPJournal2022
● Credential information in JSON format (file 'client
_
secret.json')
● Having DATA.sqlite and PREDICTION.sqlite in the same directory
● Import/install the following packages: sqlite3, datetime, timedelta, time, requests,
json, docx, Google client library, scikit-learn, pandas.
Functionality:
1. The program creates a “Day” class. In this class, the user answers the questions
about yesterday, makes necessary calculations, converts the values into suitable
formats and retrieves weather data using OpenWeatherMap API.
2. 3. Creates a sqlite database (“DATA.sqlite”) with the required columns.
Controls whether the new instance is a duplicate value. If it is a unique value, the
program appends the new instance of “Day” class into the “DATA.sqlite”
.
4. 5. Preprocesses the DATA database into a flexible dataframe
Using the dataframe, the Decision Tree calculates the sentiment based on other
inserted variables
6. 7. 8. The calculated sentiments is inserted in to PREDICTION database
Get an access to the selected Google Drive API ‘DAVPJournal’
Retrieve the list with information of files names and files IDs which are located on
the Google Drive API.
9. 10. Download chosen files from the cloud service to the current working directory.
Resize chosen images in the current directory to 1000 pxls on the longest side,
while maintaining the aspect ratio of the image.
11. Rename all files with .JPG extension to a defined format [date
_
taken]_[counter].jpg,
e.g., 2019-03-21
_
3.jpg.
12. The program makes aggregation and visualization of weekly and daily values
depending on the current date.
13. Automated word file editing with the Headings, placeholder for journaling, data
collected and earlier created graphs and photos avoiding duplicates (the installation
of “docx” package is necessary).
Authors: Recep Goktug Sengun
