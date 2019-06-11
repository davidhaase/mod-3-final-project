# Data Science Mod 3 Project:  Hypothesis Testing in Python with NYC Traffic Collision Data
#### June 11, 2019
* Linh Nguyen, David Haase (nyc-mhtn-ds-0422019)
* Flatiron School

## Project Description
This project was a exercise in hyphothesis testing for Module 3 of the Data Science Track of the Flatiron School for the nyc-mhtn-ds-04222019 cohort.  This project illustrates four hypotheses that we made on the data, and how we used ANOVA, t-Tests and chi-square analyses in Python to measure the significance of these hypotheses. 

### Assignment
The goal of this project is to test our ability to gather information from a real-world database and use our knowledge of statistical analysis and hypothesis testing to generate analytical insights that can be meaningful to the company/stakeholder.

#### Our Hypotheses
1. Do moon phases have an effect on daily collision rates in NYC?
1. Does the day of the week have an effect on daily collision rates in NYC?
1. If so, which day has the most on average?
1. How does the mortality rate of traffic collisions in NYC compare to the national average?

### Data Sources
#### NYC Traffic Collision Data
NYC OpenData: NYPD Motor Vehicle Collisions

This is a breakdown of every collision in NYC by location and injury. This data is collected because the NYC Council passed Local Law #11 in 2011. Each record represents a collision in NYC by city, borough, precinct and cross street. This data can be used by the public to see how dangerous/safe intersections are in NYC. The information is presented in pdf and excel format to allow the casual user to just view the information in the easy to read pdf format or use the excel files to do a more in-depth analysis.

* https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95

#### Moon Phase Data
The United States Naval Observatory (USNO)
3450 Massachusetts Ave, NW, Washington, DC 20392-5420

USNO strengthens national security and critical infrastructure by serving as DoD’s authoritative source for the positions and motion of celestial bodies, motions of the Earth, and precise time. USNO provides tailored products, performs relevant research, develops leading edge technologies and instrumentation, and operates state of the art systems in support of the U.S. Navy, DoD, Federal Agencies, international partners, and the general public.
* https://www.usno.navy.mil/USNO/

#### National Crash Data
National Highway Traffic Safety Administration

4 NHTSA’s National Center for Statistics and Analysis
1200 New Jersey Avenue SE., Washington, DC 20590
This fact sheet contains information on fatal motor vehicle crashes and fatalities based on data from the Fatality Analysis Reporting System (FARS). FARS is a census of fatal crashes in the 50 States, the District of Columbia, and Puerto Rico (Puerto Rico is not included in U.S. totals). 
* https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812580 

### Deliverables
#### Build Files:  Jupyter Notebooks
* [ds-mod3-final-nguyen-haase.ipynb] Start with this notebook to build collision data and moon data.

#### Data Files
* Collision Data. Collision data are not hosted here because the file is 331 MB of csv data, but you can pull them from https://data.cityofnewyork.us/resource/qiz3-axqb.json.  For the purposes of this notebook, there were saved locally as in the file: '../../Datasets/NYPD_Motor_Vehicle_Collisions.csv' 
* Moon Phases.  Moon phases from the Navy site used in this notebook are available in this repository referenced in teh file, moonphasedf.csv:

#### Conclusion and Presentation
* https://docs.google.com/presentation/d/1STg8PRsdN8YOPfCLKbWTnA2Nx6alV7CNDdMPofqsugk/edit?usp=sharing
