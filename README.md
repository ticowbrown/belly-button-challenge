# Belly Button Biodiversity Dashboard

This interactive dashboard allows users to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dataset contains information about microbial species present in different individuals' navels, identified through operational taxonomic units (OTUs).

## Features

### Demographic Information
The "Demographic Info" panel displays specific demographic information for the selected individual, including ID, ethnicity, gender, age, location, belly button type (bbtype), and washing frequency (wfreq). This information is dynamically retrieved from the dataset and updated based on the selected individual.

### Bacteria Cultures Per Sample (Bubble Chart)
The "Bacteria Cultures Per Sample" bubble chart visualizes the distribution of microbial species in a selected individual's navel. Each bubble represents a microbial species (OTU) present in the sample, with the size and color of the bubble indicating the relative abundance and OTU ID, respectively.

### Top 10 Bacteria Cultures Found (Bar Chart)
The "Top 10 Bacteria Cultures Found" bar chart displays the top 10 most abundant microbial species in a selected individual's navel. The chart provides insights into the relative abundance of these species, with each bar representing a microbial species (OTU) and its corresponding abundance.

## Implementation

### Technologies Used
- JavaScript
- D3.js (Data-Driven Documents)
- Plotly.js (JavaScript charting library)
- Bootstrap (CSS framework)

### Files
- index.html: Contains the HTML structure of the dashboard.
- app.js: JavaScript file responsible for fetching data from the dataset, building charts, and updating the dashboard based on user interactions.
- samples.json: JSON file containing the dataset with information about sample names, metadata (demographic info), and sample data (OTU IDs, labels, and values).

## How to Use
1. Open index.html in a web browser.
2. Use the dropdown menu to select an individual's sample ID.
3. Explore the demographic information, bacteria cultures per sample (bubble chart), and top 10 bacteria cultures found (bar chart) for the selected individual.
