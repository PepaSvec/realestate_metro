# realestate_metro

## About the project

This is project for a course Data This is a project for a subject Data processing in Python at Institute of Economic Studies Charles University.

Our task was to scrape data using API, process the data, visualise it and submit a github repository, while colaborating over git.

This is a project created by Marketa Mala & Josef Svec.

In this project we decided to look at realestate data from sreality.cz
 
<ul>
    <li>First we created a file spider.ipynd. This file is merely a pithc and does not have a direct effect on the data collection and processing. </li>
    <li> OPP_spider download a dataset from a dynamic webpages of sreality.cz (This is done in OOP)</li>
    <li> We obtained a messy dataset after 7 hours 20 minutes of scraping. This dataset was processed in file 
    Data_understanding_and_processing. In this file we prepared final data set 'data1.csv'</li>
    <li> The nice dataset was visualised in 'Visualisation.ipynd'</li>
</ul>

<p> 
In our process, we focused on creating a functioning code in Python.  
We were fortunate to work with a vast dataset with many variable. In the end, we focused on couple of them. 
Mostly we plotted the variables with respect to price. Visualisation.ipynb provided variety of graphs in part (A). 
Part (B) takes this analysis to another level and uses geopandas to visualise our data with the use of coordinates.
Those coordinates were obtained by converting scraped addresses into coordinates by a function in geopandas.
Our project has 3 branches that were eventually all merged into the Master branch.
</p>

PS: It would be our pleasure, if someone used our code in the future to collect data or at least used our dataset to learn about data processing. 

## Files explained
### Spider.ipynd
It is a pitch of the project. It proves the concept that scraping from sreality.cz is possible and it identifies the variables to collect. It containts our proposal and it serves as basis for OOP_spider.ipynd

### OOP_spider.ipynd
This is a object oriented crawler that can scrape sreality.cz for links of properties and latter scrape each property page individually. This jupyter notebook is used to collect our dataset. 

### Data_understanding_and_processing.ipynd
This is a jupyter notebook designed to aid our understanding of the dataset and do initial processing of the data.

### Visualisation.ipynd
This file takes the prepared data and visualize its various underlying relationships (with usual matplotlib tools as well as with geospatial tools).

### clean_data.csv
This is our final dataset  that is analysed in Visualisation.ipynb 

### scraped_dataset.csv
This file contains our full dataset that was scraped on 27.4.2020 between 9am and 5pm

### scraped_dataset_test.csv
It was a test file to see that our data are written without any errors. It is dispensable (May be deleted).

### datasetview.csv
Helps to show all variables and some values. It is used to better understand the dataset. It is dispensable (May be deleted).

### links__.__.___.csv - files
Each time we scrape links of individual properties we write the links into a csv file for a later verification and it is transparent on which days the links we collected

### TMMESTSKECASTI_P.json
This is a json file with the geometry information about Prague districts.


<footer>
Authors: Markéta Malá & Josef Švec
</footer>
