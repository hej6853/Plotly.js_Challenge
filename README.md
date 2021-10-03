# Plot.ly Challenge - Belly Button Biodiversity
Live Demo: https://hej6853.github.io/Plotly.js_Challenge--Biodiversity/

![image](https://user-images.githubusercontent.com/79428102/135770356-b1f3e530-ccb4-4343-90ab-1d822805b28a.png)

In this assignment, you will build an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Step 1: Plotly

1. Use the D3 library to read in `samples.json`.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

* Use `sample_values` as the values for the bar chart.

* Use `otu_ids` as the labels for the bar chart.

* Use `otu_labels` as the hovertext for the chart.

![image](https://user-images.githubusercontent.com/79428102/135770369-c4f55204-8578-4ee0-bae9-748a8b4ab702.png)

3. Create a bubble chart that displays each sample.

* Use `otu_ids` for the x values.

* Use `sample_values` for the y values.

* Use `sample_values` for the marker size.

* Use `otu_ids` for the marker colors.

* Use `otu_labels` for the text values.

![image](https://user-images.githubusercontent.com/79428102/135770376-a55090dd-541c-472c-a8aa-ebcefc0157ac.png)

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

![image](https://user-images.githubusercontent.com/79428102/135770389-57b58ebc-c6dd-41ec-a661-72c6fb19a75c.png)

6. Update all of the plots any time that a new sample is selected.

Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:

![image](https://user-images.githubusercontent.com/79428102/135770406-58a36c33-810f-42da-91ad-eec90f74c5d1.png)

## Advanced Challenge Assignment (Optional)

The following task is advanced and therefore optional.

* Adapt the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the weekly washing frequency of the individual.

* You will need to modify the example gauge code to account for values ranging from 0 through 9.

* Update the chart whenever a new sample is selected.

![image](https://user-images.githubusercontent.com/79428102/135770408-c7ffb806-21be-411e-90c8-4c947b63f007.png)

### About the Data

Hulcr, J. et al.(2012) _A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable_. Retrieved from: [http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)

- - -

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
