# Belly-button-challnge


Belly Button Biodiversity Dashboard



Project Overview

The Belly Button Biodiversity Dashboard is an interactive web application that visualizes microbial species data found in human navels. This project utilizes the D3 library to retrieve data from an external JSON file and employs Plotly.js to generate interactive visualizations.

Features

Horizontal Bar Chart

Displays the top 10 operational taxonomic units (OTUs) found in an individual.
The bar chart displays this data according to the Test subject id number Selected

![alt text](<Images /Horizontal bar graph.png>)


Bubble Chart

Represents the distribution and abundance of OTUs per sample.

![alt text](<Images /Bubble.png>)

Metadata Panel

Shows demographic information for each selected sample.

![alt text](<Images /Demographic data png. .png>)

Dropdown Menu

Allows users to select different individuals for analysis.

Dynamic Updates 

All charts and the metadata panel update when a new sample is selected.

![alt text](<Images /Belly button biodiversity Dashboard png..png>)

Technologies Used

HTML

CSS

JavaScript

D3.js

Plotly.js

GitHub Pages (for deployment)

Conclusion .

I have noted that a bubble chart is not the est way to prent data because it has oerapping data points.When multiple points have similar values, they may overlap, making it difficult to distinguish individual data points.The varying bubble sizes and colors may lead to misinterpretation, especially for users unfamiliar with this visualization style.Large datasets also can make the chart crowded, reducing readability.Users with color vision deficiencies may struggle to distinguish between different bubble colors.

Although the bubble chart could be used as a way of visualization, there are other better methods that would help for better readabilty for example the horizontal bar chart used , Heatmaps and Stacked Bar Charts.



