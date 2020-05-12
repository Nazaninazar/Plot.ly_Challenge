Belly Button Biodiversity

![Bacteria by filterforge.com](Images/bacteria.jpg)

In this project, I have built an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Step 1: Plotly

1. D3 library to read in `samples.json`.

2. Horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

3. Bubble chart that displays each sample.

![Bubble Chart](Images/bubble_chart.png)

4. Display of the sample metadata, i.e., an individual's demographic information.

5. Display of each key-value pair from the metadata JSON object somewhere on the page.

![hw](Images/hw03.png)

6.The plots will update any time that a new sample is selected.


![hw](Images/hw02.png)

## Advanced Challenge 

* Adapted the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the weekly washing frequency of the individual.

* Modified the example gauge code to account for values ranging from 0 through 9.

* Update the chart whenever a new sample is selected.

![Weekly Washing Frequency Gauge](Images/gauge.png)

## Deployment


* Used `console.log` inside of your JavaScript code to see what your data looks like at each step.

* Refer to the [Plotly.js documentation](https://plot.ly/javascript/) when building the plots.

### About the Data

Hulcr, J. et al.(2012) _A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable_. Retrieved from: [http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)

- - -

© 2019 Trilogy Education Services
