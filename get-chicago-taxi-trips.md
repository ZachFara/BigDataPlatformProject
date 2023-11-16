# How to get data

## Chicago Taxi Trips

1. Go to the google cloud console
2. Find the explorer tab and click '+ Add'
3. Search for 'public' and click public datasets
4. Search for the chicago-taxi-trips dataset
5. Click view dataset
6. Return to the explorer and click on the three dots next to the table you want to copy
7. Click 'Open'
8. Now click 'Export' and 'Export to GCS'
9. Specify the location, format, and compression type. Please note that a dataset which is too large cannot be loaded into your GCS as a single file. You may have to use a * marker to export your data as multiple files into a folder on your GCS
10. Return to BigQuery and then look at the bottom tab 'Job History' this should show a green check if it has competed.



