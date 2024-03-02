# belly-button-challenge
In this assignment, I built an interactive dashboard to explore [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

I did so by doing the following steps:
- Use the D3 library to read in samples.json from the URL: `https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json`
- Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual
    - Use `sample_values` as the values for the bar chart.
    - Use `otu_ids` as the labels for the bar chart.
    - Use `otu_labels` as the hovertext for the chart.
    - ![hw01](https://github.com/karandogra1721/belly-button-challenge/assets/150204834/516ab7a4-a7b8-4b00-8a26-1f7193f07c34)
- Create a bubble chart that displays each sample.
    - Use `otu_ids` for the x values.
    - Use `sample_values` for the y values.
    - Use `sample_values` for the marker size.
    - Use `otu_ids` for the marker colors.
    - Use `otu_labels` for the text values.
    - <img width="1416" alt="bubble_chart" src="https://github.com/karandogra1721/belly-button-challenge/assets/150204834/b34879ca-e5f8-4f67-bb4c-40d36bb92bf3">
- Display the sample metadata, i.e., an individual's demographic information.
- Display each key-value pair from the metadata JSON object somewhere on the page.
- ![hw03](https://github.com/karandogra1721/belly-button-challenge/assets/150204834/614a569c-1b3c-4f5c-a5ae-cb38c83a9709)
- Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:
- ![hw02](https://github.com/karandogra1721/belly-button-challenge/assets/150204834/0b9b2113-9683-456d-b99b-f86913340a61)
- Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

## Advanced Challenge Assignment
The following task is advanced and therefore optional.
- Adapt the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the weekly washing frequency of the individual.
- You will need to modify the example gauge code to account for values ranging from 0 through 9.
- Update the chart whenever a new sample is selected.
- <img width="384" alt="gauge" src="https://github.com/karandogra1721/belly-button-challenge/assets/150204834/c626e2d5-2cc9-4ed9-b2cd-d4d5f36aaa10">




