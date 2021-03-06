Happiness
===

Basic Information
---
- Project title: Happiness
- Authors: Samuel Coache, Samantha Comeau, William Schwartz
- Emails: sccoache@wpi.edu, sjcomeau@wpi.edu, wrschwartz@wpi.edu
- Github Usernames: sccoache, sjcomeau43543, williambannas
- Repository: https://github.com/sjcomeau43543/DataVisFinal 
- link: https://sjcomeau43543.github.io/DataVisFinal/

Background and Motivation
---
The motivation for choosing this project was to determine what factors make people happy.  We saw a dataset of how people ranked themselves on their happiness and decided we wanted to try to correlate that data to other factors, like the regions favorite extracurricular activities, historical events, family size, alcohol consumption, etc, and try to determine what factors are most important to reported happiness.  We have reviewed some of the other happiness reports out there, and believe they report the data, but don’t got far enough exploring what social, economic, and environmental factors contribute to those results. We believe that we can present this information in a visually appealing and informative manner to help distinguish some of the ambiguity. 

Project Objectives 
---
Some questions we are trying to answer through our exploration data visualizations are as follows.

- What makes people happy? 
- How does happiness compare across the world?
- What differences between countries cause certain countries to be happier?
- How does self perception (pessimism, view of others) affect accuracy of how happy people think they are?

We chose this data because we want to learn about reported happiness and what factors affect said happiness.  

We want to break our data into a few main categories and see how these categories affect overall happiness.

Extracurricular participation
- What do people in these countries do in their free time?
- Do they participate in country-wide events like the Olympics or Car-Free days?
- How much alcohol do they consume?

Life factors
- Whats the overall population of their country?
- This could affect their self reflection on how much they can impact the world etc
- How large is the average family?
- How long are they expected to live?

Monetary factors
- GDP
- What is the unemployment rate?
- Has inflation affected their happiness? Stress?

A benefit of comparing these different categories is that it allows us to see more of the whole picture.  Rather than solely focusing on something like socio-economic status or unemployment rates we can see how personal life and business life affect humans happiness, because overall, everything in their life is affecting them somehow.  We hope to use these categories to compare the different countries to learn what is most benefiting their happiness and what is making them less happy.  For example say America has a binge drinking problem and their happiness score is very low, and France doesn’t drink as often and their happiness is high.  One intermediate conclusion could be that drinking affects happiness.  Adding these intermediate conclusions together with the rest of the categories conclusions will show us the big picture on what factors truly contribute to an individual’s happiness. 

Data
---
We found a data set on Kaggle.com representing world happiness scores.  However this dataset didn’t have some of the other factors we wanted to integrate so we found other datasets to use in conjunction with the main dataset.

All of our datasets are in the data/ folder in the project repository.

Some resources we used to find these sites include:
- http://www.pewglobal.org/search/?query=happiness
- https://www.kaggle.com/unsdsn/world-happiness/data
- http://worldhappiness.report
- http://www.imf.org/external/index.htm

Data Processing
---
We plan on using python scripts to cleanup any data we don’t need. This will include removing columns we don’t need from our datasets for certain visualizations to increase efficiency while loading the data.  We definitely will need to remove a lot of unneeded data.  

Some of our data sheets have missing data points for a few years of certain countries.  We will have to remove this data before using it so that we can save space and time when loading our data into our project.

By making python scripts to do this for us we can choose what data we want to keep, put it in a for loop and just let it run. If we were to manually remove all the data we don’t need it would take hours to do but this way we will save time and effort.  We will have to check for corner cases and make sure the data was filtered properly.

We plan to get all of the categories mentioned above from our various data sets.  This includes per country data for average alcohol consumption, average family size, quantity participation in the olympics and car-free days,  the unemployment rate, and more.  We plan to store these values in respective csv files so we can keep everything clean and seperated.  This will help with organization and loading data into separate variables for consistency.

Visualization Design
---
Originally we had started by choosing 2 set graphs as below.

We plan on using somewhat of a story-telly technique to display our data.  Since we have so many different factors to display we want to start by showing the overall happiness per country in a simple choropleth map similar to below.

![cloropleth_example](img/proposal/cloropleth.png)

We want the users to be able to interact with the data a little so we want to show happiness over time in a line graph for the selected country / continent in a line chart.

![linechart_example](img/proposal/linechart.png)

For each of our sub categories we plan to use a few different visualization techniques.

We want to start with life factors because this seems the most important and impactful on people. 
- Overall population
- Average family size
- Life expectancy

For monetary factors we will display and analyze them in more charts.
- GDP
- Unemployment
- Inflation vs happiness over time in a line chart

Finally for extra curricular activities we will display them in the following charts.
- Alcohol consumption
- Participation in country wide-events

Then we decided to use the 5 design sheet method of deciding on our design because we were stuck on what we wanted to do.

This produced our brainstorming sketches.
![Sam](img/proposal/sam_brain.JPG)
![WIll](img/proposal/will_brain.JPG)
![Coache](img/proposal/coache_brain.JPG)

We then made 3 potential designs from those.
![Design1](img/proposal/Design1.JPG)
![Design2](img/proposal/Design_2.JPG)
![Design3](img/proposal/Design_3.JPG)

and we chose...
![Final](img/proposal/Final.JPG)

Features
---
### Must-Have Features

- Geographical mapping of all countries and reported happiness
- Comparisons between top and bottom happiness ranked countries compounded with other significant factors to determine what makes people happy
- Some sort of interaction with the data so the user can make their own conclusions.

### Optional Features
- Selection to compare 2 countries happiness, to all compounding data 
- One cumulative chart with everything layered on it vs the happiness chart


Project Schedule
---

#### Milestone 1: 
- Description: Completed charts with proper data input (color scheme not important)
- Deadline: Wednesday 2/21 4PM
- Meeting times:
-- Sunday 12-5 PM
-- Monday 6-7:30 PM

#### Milestone 2: 
- Description: Adding intermediate observations
- Deadline: Friday 2/23 11:59 PM
- Meeting times: 
-- Wed 6-7:30 PM
-- Wed 8:30-10 PM
-- Thursday 6-8 PM

#### Milestone 3: 
- Description: Add color and interactions and format the rest of the webpage
- Deadline: Sunday 2/25
- Meeting times: 
-- Friday 1-5 PM
-- Sunday 12-5 PM

#### Milestone 4: 
- Description: Presentation materials
- Deadline: Wednesday 2/27
- Meeting times: 
-- Monday 6-7:30 PM
-- Tuesday 4-8 PM

![when_to_meet](img/proposal/wtm.PNG)



