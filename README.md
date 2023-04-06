# belly_button_challenge

This is an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
Dashboard Features
Drop Down Menu

Select the Test Subject ID No. with the drop down menu to toggle the visualizations (bar, gauge, bubble charts)
![hw03](https://user-images.githubusercontent.com/118322641/230405601-d1993542-2150-4f56-a8aa-240c2b20eb16.png)

Demographic Info Panel

This Panel shows the demographics information of the chosen test subject
Displays each key-value pair from the metadata JSON object

![hw01](https://user-images.githubusercontent.com/118322641/230405801-2477992c-ad1f-413c-8206-6f04ad7bf68b.png)

A bar chart is generated when a test subject is selected on the drop menu
The top 10 OTUs found in that test subject will be displayed in bars, where the sample_values are presented as the values for the bar chart and the otu_ids presented as the labels for the bar chart
When a user hover over a bar, the otu_labels are presented as the hovertext for the chart

<img width="384" alt="gauge" src="https://user-images.githubusercontent.com/118322641/230405856-a9e5a6dc-9952-482a-9876-df60108bbf86.png">


A gauge chart is generated when a test subject is selected on the drop menu
The value of srubs per week (wfreq) is display on chart with a blue colored bar
image

<img width="1416" alt="bubble_chart" src="https://user-images.githubusercontent.com/118322641/230405926-7f0d4478-37ed-4d97-a850-158c8e3dc27e.png">


A bubble chart is generated when a test subject is selected on the drop menu
Each sample will be display as a bubble, where the larger the sample value is the larger the bubble size
On the chart, the x values are the otu_ids, the y values are the sample_values
The colors of the bubbles are based on otu_ids, and the hovertext are the otu_labels
