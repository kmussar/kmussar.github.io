---
layout: post
title: First blog post
---

### Metis Project #1: 
##  Optimizing Marketing at New York MTA Stations

The goal of this project was to identify the optimal stations to place street teams in order to recruit people to attend a fictioal women in technology gala. The gala was to take place in New York City in the early summer and we were to use the MTA turnstile data in our analysis. 


## Approach
1. Define target audience
2. Identify stations used by the target audience
3. Within our filtered stations, choose those with the highest volume of traffic.  


#### **Target Audience** 
We assumed that the following groups would be likely to attend a women in technology gala: 
* Women working in technology fields
* Other genders working in technology fields
* Women employed in other fields
* Students


## The Data
To complete this project, we used the following 5 data sources: 
* NYC Open Data's [Demographics and profiles at the Neighborhood Tabulation Area (NTA) level](https://data.cityofnewyork.us/City-Government/Demographics-and-profiles-at-the-Neighborhood-Tabu/hyuz-tij8) 
* NYC Open Data's [NTA Map](https://data.cityofnewyork.us/City-Government/NTA-map/d3qk-pfyz/data) 
* NYC Open Data's [Subway Stations Map](https://data.cityofnewyork.us/Transportation/Subway-Stations/arq3-7z49/data) 
* [Google Maps](https://www.google.com/maps)
* NYC's [MTA Turnstile Data](http://web.mta.info/developers/turnstile.html) 

## Data Cleaning and Exploratory Data Analysis
My Jupyter notebook for Data Cleaning and EDA can be found [here:](https://github.com/kmussar/metis_project_benson/blob/master/Project%201_demographics_Clean.ipynb) 
### Determine which neighborhoods our target audience lives, works, or goes to school in. 
#### **Using NTA data to idenfiy neighborhoods with the highest perecentage of employed women, and the highest number of employed people in technology live.**
Neighbhorhood tabulation areas (NTAs) are subdivisions of New York City used in census data. This dataset from the New York City government describes the demographics in each area.
Columns include:
* Employment Status
* Occupation Industry
* Age 
* Gender
* If they have children
* Income
* Health Insurance Coverage

The features I focused on specifically are:
* Percentage of civilian employed population 16 years and over in region in management, business, science, and arts occupations. 
* Percentage of females 16 years and over in the labor force

I used the threshold 70% to filter out the subdivisions of interest because this number seems high enough that a member of a street team would encounter someone in their target audience by chance.

Below are figures depicting the the % of target demographics per subdivision. (Subdivisions are not labeled due to the high # present). 

Percent of employed people residing in the district working in management, business, science, and arts
![graph]
(https://github.com/kmussar/metis_project_benson/blob/master/districts_industry.png)

females 16 years and over in the labor force
![graph](https://raw.githubusercontent.com/kmussar/metis_project_benson/master/districts_women.png)

I sorted the subdivisions based on the % of the population  of 
Of {% highlight text %} 
### 
{% endhighlight %}
subdivisions 

### Idenfity the MTA subway stations that are located in these subdivisions

### Calculate the volume of traffic for each subway station. 



### Filter 



## Our recommendations



## Challenges & Future Directions
* Automatically determine which neighborhood a station is in. 
* Explore other demographic data for potential attendees
* Optimize recommendations for day of week and time of day 
* Use feedback collected from initial test runs to inform the future runs. 
* Use online resources such as Meetup.com and LinkedIn to promote the event. 



## Future directions 
 

  
