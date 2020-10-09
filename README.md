# Sqlalchemy and Flask API - Advanced Data Storage and Retrieval

Used Sqlalchemy to connect to a Hawaii weather sqlite database, then reflected tables into classes and saved as references Station and Measurement. Next, analysis was performed on different stations and measurement queries. For the second part of the challenge, designed a Flask API based on queries performed in the first step, and used Flask to create API routes. 

## Table of contents

* [Technologies](#technologies)
* [Installation](#installation)
* [Development Process](#development-process)
* [Data Sources](#data-sources)
* [Contact](#contact)

## Technologies
* Python - version 3.7.6
  * Numpy - 1.18.5
    * mean
  * Matplotlib - 3.2.2 
    * inline - to store plots within jupyter notebook
    * Style - import fivethirtyeight style
    * Pyplot
  * Pandas - 1.0.5
  * Scipy
    * stats
  * datetime
* Sqlalchemy - version 1.3.17
  * automap_base
  * Session
  * create engine
  * func
  * inspect
* Flask
  * jsonify

## Installation and Usage


## Development Process

* Used d3 to bind the data to the HTML document and build interactive visualizations including charts, a panel of demograpic information, and a dropdown menu to select different test subjects:

  ![Dropdown Menu](images/dropdown_menu.png)
* Used Plotly to create interactive chart visualizations including: 
1. a horizontal bar chart displaying the amount of the 10 most prolific bacteria found in the test subject's belly button.
  ![Horizontal Bar Chart](images/horizontal_bar_chart.png)
2. a bubble chart to visualize the amount of each bacteria, scaled to the quantity found.
  ![Bubble Chart](images/bubble_plot.png)
3. a gauge to visualize the amount of times the test subject washes their belly button a week.
  ![Washing Gauge](images/washing_gauge.png)

## Data Sources
* [Link to local Belly Button Data](samples.json)
* Data sourced from: Hulcr, J. et al.(2012) _A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable_. Retrieved from: [http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)

## Contact
Created by [Katy Luquire](https://github.com/CatherineLuquire)
