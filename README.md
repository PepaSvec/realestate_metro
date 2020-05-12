# realestate_metro

### About the project
This is a project for a subject Data processing in Python at Institute of Economic Studies Charles University.

This project's aim is to analyse the relationship between the rents and distance from metro station.

1) First step is to create a web crawler to collect our data from a certain advertisement 

2) process data

3) visualize it


### Files explained

#### Spider.ipynd
It is a pitch of the project. It proves the concept that scraping from sreality.cz is possible and it identifies the variables to collect. It containts our proposal and it serves as basis for OOP_spider.ipynd

#### OOP_spider.ipynd
This is a object oriented crawler that can scrape sreality.cz for links of properties and latter scrape each property page individually. This jupyter notebook is used to collect our dataset. 

#### Data_understanding_and_processing.ipynd
This is a jupyter notebook designed to aid our understanding of the dataset and do initial processing of the data.

Work in progress...

#### links__.__.___.csv - files
Each time we scrape links of individual properties we write the links into a csv file for a later verification and it is transparent on which days the links we collected

#### dataset.csv
This file contains our full dataset that was scraped on 27.4.2020 between 9am and 5pm

#### dataset_sample.csv
It was a test file to see that our data are written without any errors. It is dispensable (May be deleted).

#### datasetview.csv
Helps to show all variables and some values. It is used to better understand the dataset. It is dispensable (May be deleted).


## To - do

<ul>
    <li> Continue working in Data_understandign_and_processing </li>
    <li> Settle on relationship that we can visualize </li>
    <li> How can we get a Prague map in geopandas </li>
    <li> Understand wheater we can plot address with geopandas (if not, we have to use google maps api to convert address to coordinates)</li>
</ul>

<footer>
Authors: Markéta Malá & Josef Švec
</footer>