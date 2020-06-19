# Geo_heatmap

This is a repository for teaching data science students how to get the location data from google and use it to make a geo heatmap with folium.
This repository is a simplifyed student-friendly version of the repository created by luka1199 https://github.com/luka1199/geo-heatmap

If you don't already have Python 3.8 or higher and jupyter notebook for this repository

### 2. Get Your Location Data

Here you can find out how to download your Google data: <https://support.google.com/accounts/answer/3024190?hl=en></br>
Here you can download all of the data that Google has stored on you: <https://takeout.google.com/>
Make sure you select to download your location data as a .json file!


### 3. Create your own geo heat map 

After you get your location history from google, replace the Location_History.json file with your own Location History file.

Run the jupyter notebook script geoheatmap_students.ipynb

In your bash terminal, install the requirements:

	pip install -r requirements.txt

To protect your privacy: Do not push your own Location History file or the .html output file to this repository!

![alt text](heatmap.png)
