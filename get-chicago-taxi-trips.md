# How to get data

## Chicago Taxi Trips

1. Go to the google cloud console
2. Find the explorer tab and click '+ Add'
   ![image](https://github.com/ZachFara/BigDataPlatformProject/assets/57742350/e6c0de8e-0679-444b-b11d-e16170247db2)
4. Search for 'public' and click public datasets
   ![image](https://github.com/ZachFara/BigDataPlatformProject/assets/57742350/b971d1a9-76d0-4999-b976-aa98c24fac08)
6. Search for the chicago-taxi-trips dataset
7. Click view dataset
8. Return to the explorer and click on the three dots next to the table you want to copy
9. Click 'Open'
10. Now click 'Export' and 'Export to GCS'
11. Specify the location, format, and compression type. Please note that a dataset which is too large cannot be loaded into your GCS as a single file. You may have to use a * marker to export your data as multiple files into a folder on your GCS
12. Return to BigQuery and then look at the bottom tab 'Job History' this should show a green check if it has competed.



