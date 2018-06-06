Happiness
===


Basic Information
---
- Site Link: https://sccoache.github.io/Worldwide_Happiness_Visualization/


Overview
---
For this project we created a webpage that allows people to interact and see why some countries are happier than others. To complete this task we started collecting readily available country specific metrics that we believed  could cause a certain country’s inhabitants to be relatively more or less happy. The data that we gathered was the reported average reported happiness by country, total population, Gross Domestic Product (GDP), inflation, unemployment, and alcohol consumption, all of this data was gathered from the year 2008 to 2016. We wanted to present this data in a way that would allow people to engage, and explore on their own. We broke our visualization into three distinct sections:

The first is a choropleth map showing the reported happiness of each country using a blue gradient. Darker blue being happier, and lighter blue meaning a country is less happy. Users are able to click through years, and see how reported happiness changes, as well as compare happiness visually to adjacent countries, by clicking on the country, hovering over a Country brings up a tooltip displaying the reported value.

The second interaction was our most experimental interaction. We created a cluster chart of all the countries with reported happiness data. Using the same blue color scale from the map to relate to the reported happiness. We also arranged the data in this chart to show the countries organized from unhappy to happy. Hovering over these points displays a tooltip, which like previous displays the country name and the reported happiness score. Sliders for each of our factors are presented on the side of cluster chart and are used to filter counties that are displayed, and give the user a chance to explore and look for correlation between factors on their own.

The third section, is a series of sorted colored bar charts, where the color corresponds to the value, presenting the data this way gives the user somewhat of an indication of the distribution of each of the factors very quickly. The graphic also serves to show easily how countries rank in specific categories. When hovering over a specific bar, you the bar gets highlighted, and the same country also gets highlighted in all the other factors charts, and  see how countries compare to one another. Like in the other sections the mouse over also displays a tooltip, to show the country name as well as well as displaying the value of that factor selected.


Outside Libraries/References
---
http://d3js.org/d3.v4.min.js

https://d3js.org/d3-scale-chromatic.v1.min.js

https://d3js.org/topojson.v1.min.js

https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js

