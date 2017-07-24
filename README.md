Brick and Mortar (B&M) service providers are at disadvantage, compared to  online service providers, partly due to the advanced customer activity aware (analytics) access online providers have on customers.  To stay competitive and remain profitable B&M companies have to employ smart networks (smart WiFi) to integrate analytics as one of their lever towards operational efficiency.

 This dashboard is built, as proof of concept,  for a fictional brick and mortar franchise shop that is fitted with intelligent WiFi access point in each of the 20 locations throughout the United States. Disclaimer: The data is dummy data and is manually generated.
 
This Web app uses a **Flexdashboard** (by R studio) framework that enables it to render interactive dashboard to visualize data. The data for this maps emulate Meraki smart WiFi JSON data.    The dashboard integrates 5 html widgets and use the pub/sub concept to have the 5 widgets in the app interact simultaneously, powered by the crosstalk package from rstudio.   Each of the 5 widgets can also interact within itself without having to interact with the other html javascript widgets. 

The frame work for this app uses the following html widgets:
. Leaflet iopen-source JavaScript libraries for interactive maps
. Plotly - for the bar and donut charts
. Data Table - to render the raw data table
. gamer of graphics 2 (ggplot2) - to render the bar charts

For more information, take a look at the reveal js markdown presentation. If you have further question drop me an e-mail or contact me @abiyugiday on twitter.
