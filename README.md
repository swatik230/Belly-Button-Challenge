# Belly-Button-Challenge

Background
In this assignment, you will build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Before You Begin
Create a new repository for this project called belly-button-challenge. Do not add this Challenge to an existing repository.

Clone the new repository to your computer.

Inside your local git repository, copy the files from in the StarterCode folder contained within the Module 14 Challenge zip file. i.e. index.html, samples.json, and the static folder.

NOTE
You will not be required to access the samples.json file locally, but it is provided for reference.

Push the above changes to GitHub.

Deploy the new repository to GitHub Pages.

Files
Download the following files to help you get started:

Instructions
Complete the following steps:

Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

Use sample_values as the values for the bar chart.

Use otu_ids as the labels for the bar chart.

Use otu_labels as the hovertext for the chart.

![image](https://github.com/swatik230/Belly-Button-Challenge/assets/88855120/bebbeb02-eb54-41a0-966f-b955d15a1117)
Create a bubble chart that displays each sample.

Use otu_ids for the x values.

Use sample_values for the y values.

Use sample_values for the marker size.

Use otu_ids for the marker colors.

Use otu_labels for the text values.


![image](https://github.com/swatik230/Belly-Button-Challenge/assets/88855120/7fdada0b-8fad-42e4-9107-90e013dc922e)

Display the sample metadata, i.e., an individual's demographic information.

Display each key-value pair from the metadata JSON object somewhere on the page.

![image](https://github.com/swatik230/Belly-Button-Challenge/assets/88855120/29a724d3-2daa-459f-a761-ea691b20e5cc)


Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:


![image](https://github.com/swatik230/Belly-Button-Challenge/assets/88855120/36e44c7b-747d-4cd6-b961-c0e9e0bbecf7)


![image](https://github.com/swatik230/Belly-Button-Challenge/assets/88855120/c1518220-cd12-451b-b54b-d43d3248655e)

Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file
