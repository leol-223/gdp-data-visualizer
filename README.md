# Global Economic Trends Visualizer

![Processing](https://img.shields.io/badge/Built%20With-Processing-blue)

A legacy project (2021) exploring global economic trends through data visualization.

<img src="gdpGrowthBarGraph/GDP Per Capita Growth (2000-2020).png" width="100%">

## About
This is a data visualization tool designed to track **GDP (per capita)** growth over time. It renders a bar graph showing which countries saw the largest percentage jump in GDP between 2000 and 2020.

I originally developed this in 2021 (8th grade) to explore the Processing environment and data analysis logic.

## Key Features
*   **Dynamic Rendering:** Bars are rendered automatically based on the data, with customizable variables for resolution and spacing.
*   **Flag Integration:** The graph displays country flags for context.
*   **Color Algorithm:** Bar colors are generated based on the **average color of each flag**, making the countries easily distinguishable.

## Technologies Used
*   **Environment:** Processing (Java)
*   **Data Format:** CSV

## Data Source
*   **Source:** World Bank Open Data
*   **Dataset:** Nominal GDP Per Capita
*   **Link:** [World Bank Data (2000-2020)](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD?end=2020&start=2000)

*Note: Data visualized here may vary slightly from current records as the World Bank occasionally revises data retrospectively.*

## How to Run

**Prerequisites:** [Processing IDE 3.0+](https://processing.org/download)

1.  Clone the repo:
    ```bash
    git clone https://github.com/leol-223/gdp-data-visualizer.git
    ```
2.  Open the project folder:
    *   Navigate to `gdpGrowthBarGraph` -> `gdpGrowthBarGraph.pde`
3.  Open the file in the Processing IDE and run the sketch.
