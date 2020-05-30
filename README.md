# realestate_metro

## About the project
This is a project for a subject Data processing in Python at Institute of Economic Studies Charles University.

This project's aim is to analyse the relationship between the rents and and various aspects (such as adress or closeness to "Cukrárna").

1) First step is to create a web crawler to collect our data from a certain advertisement 

2) Process data

3) Visualize it


## Files explained

### Spider.ipynd
It is a pitch of the project. It proves the concept that scraping from sreality.cz is possible and it identifies the variables to collect. It containts our proposal and it serves as basis for OOP_spider.ipynd

### OOP_spider.ipynd
This is a object oriented crawler that can scrape sreality.cz for links of properties and latter scrape each property page individually. This jupyter notebook is used to collect our dataset. 

### Data_understanding_and_processing.ipynd
This is a jupyter notebook designed to aid our understanding of the dataset and do initial processing of the data.

### Visualisation.ipynd
This file takes the prepared data and visualize its various underlying relationships (with usual matplotlib tools as well as with geospatial tools).

Work in progress...

### links__.__.___.csv - files
Each time we scrape links of individual properties we write the links into a csv file for a later verification and it is transparent on which days the links we collected

### dataset.csv
This file contains our full dataset that was scraped on 27.4.2020 between 9am and 5pm

### dataset_sample.csv
It was a test file to see that our data are written without any errors. It is dispensable (May be deleted).

### datasetview.csv
Helps to show all variables and some values. It is used to better understand the dataset. It is dispensable (May be deleted).

### TMMESTSKECASTI_P.json
This is a json file with the geometry information about Prague districts.


## To - do

<ul>
    <li> Finish the (B) part of visualizations. [Markéta] </li>
    <li> We have couple of proposed visualizitaions in the part (A), now it needs to be discussed (what do we really want to focus on, maybe we can skip some boring parts, or on the other hand decide to go more in depth in some parts... [during the Thuesday call] </li>
    <li> As soon as we discuss the above, the finalization phase comes - we need to tidy up the descriptions in the Visualization file. [together till Thursday] </li>
</ul>
<br>
<footer>
Authors: Markéta Malá & Josef Švec
</footer>
