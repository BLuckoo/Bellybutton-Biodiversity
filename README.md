<p align="center">
<img width="898" alt="BBIntro" src="https://user-images.githubusercontent.com/82583576/126011235-a723f406-c8b5-4566-a7ea-b7f071ff6352.PNG">
</p>

# Belly Button-BioDiversity

## Introduction ##

An interactive dashboard has been developed to present the findings of a study done on the diversity of microbials living in human navels.

For the purposes of this project the Research Dataset has been provided in a JSON file, and the dashboard has been developed using JavaScript, HTML, CSS and Plotly librairies.
Some of the features of the website include:
-   Customization of the background colour - grey has been used following the clients's choice as well as it provides a good contrast.
-   Use of microbials image as an illustration.
-   A short summary of each chart has been provided above the chart.
-   A fixed navigation bar has been inserted at the top of the page - allowing for the navigation bar to always be visible. Each option on the navigation bar changes colour when selected and the user is directed to the relevant section of the website.
-   When the website is refreshed, the first participant's details will show up on the site. As the participant ID is selected in the drop down menu, all the charts are updated accordingly.


## Brief Summary of the Contents of the Website ##

The participants in the research have been provided with a "Test Subject ID No:" which they can use to access their demographic data and see the level and types of microbials found in their navels.

The following information is available from the web site:

1. Demographic Info as per the chart below which shows the information provided by the participant
<p align="center">
    <img width="114" alt="Demographic Info" src="https://user-images.githubusercontent.com/82583576/126014431-1c8e4e02-727a-4077-a835-4be47e5f6cbc.PNG">
 </p>
    
2. A horizontal bar chart using the sample results collected for the said participant showing the top ten bacteria cultures found is also provided on the web page. As the participant hovers each bar on the chart, information with regards to the type and quantity of "Operational Taxonomic Units" (OTU's) - which is a group of organisms - found in the navel is published.
<p align="center">
    <img width="678" alt="Top_10" src="https://user-images.githubusercontent.com/82583576/126014871-8e07439e-0eea-4039-b94e-ac7514105091.PNG">
</p>

3. The quantity of each OTU in the sample is illustrated in a bubble chart. Each bubble's size is proportional to the quantity of bacteria in the sample.
<p align="center">
  <img width="683" alt="Bacteria_Cultures" src="https://user-images.githubusercontent.com/82583576/126015199-0f9b86b2-fccc-4314-8972-0eec88e70822.PNG">
</p>

4. The dataset also included the weekly wash frequency for each participant. This information is displayed using a gauge meter as illustrated below.
<p align="center">
    <img width="416" alt="Gsuge" src="https://user-images.githubusercontent.com/82583576/126015334-45ced59a-e315-430f-8719-df8f5b9c9ad2.PNG">
</p>

The website has been deployed using GitHub pages and the url is as follows: https://bluckoo.github.io/Bellybutton-Biodiversity/ 


