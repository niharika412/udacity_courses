The notebook is the implementation of the final project done after Udacity's "Data Wrangling with MongoDB" Nanodegree where the following steps are performed to make the data ready for insertion into the database:

🎈 Data Extraction for any specific area from openstreetmap.org

🎈 Data cleaning 

🎈 Data Analysis for understanding the data even more

🎈 Preparation of the data for the database

🎈 Conversion of data from HTML/XML format to easily readable, JSON format

Here, all of the data available within the city boundary of Virar- West (Mumbai, India) was extracted from the [OpenStreetMap](https://www.openstreetmap.org/)  Project.
After extracting the data, it was examined and all nodes were extracted individually for information like addresses, types, users etc.
The most active users who had contributed a large amount of times were also determined.
Finally, the data was arranged in form of key-value pairs (python dictionaries) and then eventually converted into the .json format.

🗺 map.osm = Initial raw data from source
🗺 map.osm.json = Final wrangled data 
