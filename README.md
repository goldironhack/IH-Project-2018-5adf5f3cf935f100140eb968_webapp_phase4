﻿# Projectsito ![CI status](https://img.shields.io/badge/build-passing-brightgreen.svg)

Projecsito is a project made for 'Purdue UNAL IronHacks' contest, Spring 2018. 

## Keywords

`Creativity` `Design` `Students` 

## Description of the datasets and function design

* `Neighborhood Names GIS` [Link](https://data.cityofnewyork.us/api/views/xyye-rtrs/rows.json?accessType=DOWNLOAD) **Topic:** _Area_ **Columns used:** `the_geom` `borough` `name`
* `Dataset contains information on New York City housing by building data` [Link](https://services5.arcgis.com/GfwWNkhOj9bNBqoJ/arcgis/rest/services/nycd/FeatureServer/0/query?where=1=1&outFields=*&outSR=4326&f=geojson) **Topic:** _Area_ **Colums used:** `BoroCD` `geometry` 
* `Crimes in NY` [Link](https://data.cityofnewyork.us/resource/9s4h-37hy.json?cmplnt_fr_dt=2015-12-31T00:00:00.000) **Topic:** _Safety_ **Colums used:** `boro_nm` `ofns_desc` `lat_lon` `latitude` `longitude` `cmplnt_fr_dt`
* `Dataset contains information on New York City housing by building data
` [Link](https://data.cityofnewyork.us/api/views/hg8x-zxpr/rows.json?accessType=DOWNLOAD) **Topic:** _Housing_ **Colums used:** `borough` `lat` `long` `Extremely Low Income Units` `project_name`
 `street` `Construction type`
* `Museums dataset
` [Link](https://data.cityofnewyork.us/api/views/fn6f-htvy/rows.geojson) **Topic:** _Leisure_ **Colums used:** `name` `coordinates`
* `Neighborhood tabulation
` [Link](https://data.cityofnewyork.us/resource/q2z5-ai38.geojson) **Topic:** _Area_ **Colums used:** `coordinates`

## Brief Description
### Introduction
This is projectsito. The solution for the task proposed in the contest. It's meant to meet the minimum requirements of the task while keeping creativity and imagination. It's important to Projectsito to be user-friendly and to help people to find a home to live.
### Meeting the requirements

* Map View:
1. [Y] Basic Map is located in NYU Stern Bussiness school.
2. [Y] The map displays a heat map cover for Crime history.
* Data Visualization:
1. [Y] Charts and tables have been implemented.
2. [Y] Liquid Charts have been implemented. So do the tables.
* Interaction Form: 
1. [Y]
* The map displays information about neighborhoods when a neighborhood marker is clicked.
* The map displays information about a crime when a crime marker is clicked.
* The map displays information about housing when a housing marker is clicked.
* If the bouncing icon is clicked, it shows up _"NYU Stern Business School"_.
2. [N] There's no other operation except for map-related ones.
3. [N] There's no information input.
4. [Y]
* The map can display all neighborhood group by borough.
* The map can display all housing units group by borough.
* The map can display all crimes group by borough.
* The map can display all three parameters by top 10.
5. [Y]
* The map can zoom in or zoom out when a marker is clicked or double-clicked respectively. 

## Build Case
In order to use the project you simply should download every file and folder from the project and execute `index.html` with a valid web browser.

## Test Case 
Projectsito has only been tested on Chrome browser on a screen of `1920x1080`.

## Additional Info
I didn't have the progress I would like to have. But I'm pretty sure I'm ok with every functional requirement.