## testCoronavirus
The idea behind this project is to utilize GPS history to approximate the probability of having contracted the Coronavirus disease (COVID-19). This requires GPS history repository of confirmed patients which is subject to be available based on the decision of the government to share the required masked information. 

INPUT:

Infected.json : Masked GPS history of all confirmed patients stacked together

Test.json     : Masked GPS history of the person to be checked

Here, the json files are dummy files created as placeholders. Please replace the files with your own. 

Pickle files have been uploaded for demo purpose. load_pickle arguments of the class needs to be True to use pickle files instead of json.

The GPS history can be downloaded through Google Takeout. Steps to download Location History:

1. Visit Google Takeout(https://takeout.google.com/settings/takeout) to download your GPS history. There is a list of datasets to choose from, on the Google Takeout page. Deselect all and then just select 'Location History'.

2. Scroll to the end of the page and click on next which will take you to the next step.

3. Here you find options to configure the delivery method, file type & size, and frequency.

4. After selecting the file type(json), file size, delivery method and frequency, click on 'Create Export'. The time for export creation depends on the amount of data involved. Google Takeout sends an email to the corresponding Google account as soon as the export creation is completed. I was able to get the data within 15 minutes.

5. When the export has been successfully created, click on the download button to save it.

The required json file can be found at: zipfile > 'Takeout' > Location History > Location History.json


