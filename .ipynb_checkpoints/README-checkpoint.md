
# EV Charging and Sales Data Analysis

## Project Overview
This project analyzes **electric vehicle (EV) charging infrastructure** and **EV sales** data collected by the US Government's **Alternative Fuels Data Center** over a ten-year period. The data includes records of both **public and private EV charging ports** and station locations, as well as **yearly sales of electric vehicles** by model in the United States. The aim of this project is to uncover trends in the EV market, understand how EV infrastructure is growing, and provide insights that can guide strategic decisions for network operators.

## Datasets

### 1. `private_ev_charging.csv`
This dataset provides the yearly count of privately owned EV charging ports and station locations.

| Variable                  | Description                                                                  |
|---------------------------|------------------------------------------------------------------------------|
| `year`                    | Year of data collection                                                      |
| `private_ports`            | Number of charging ports owned by private companies                         |
| `private_station_locations`| Number of privately owned station locations for EV charging                 |

### 2. `public_ev_charging.csv`
This dataset records the number of publicly owned EV charging ports and stations for each year.

| Variable                  | Description                                                                  |
|---------------------------|------------------------------------------------------------------------------|
| `year`                    | Year of data collection                                                      |
| `public_ports`            | Number of charging ports under public ownership                              |
| `public_station_locations`| Number of publicly owned station locations for EV charging                   |

### 3. `ev_sales.csv`
This dataset contains the sales information for various EV models across the years.

| Variable  | Description                                           |
|-----------|-------------------------------------------------------|
| `Vehicle` | Electric vehicle model                                |
| `year`    | Year of data collection                               |
| `sales`   | Number of vehicles sold in the US                     |

## Project Goals
- **Visualize Trends**: Analyze the growth of EV charging infrastructure, comparing public vs. private installations over the years.
- **Sales Analysis**: Understand EV sales trends by model and year, identifying popular vehicle models and market growth.
- **Strategic Insights**: Provide insights into the correlation between the growth of charging infrastructure and EV sales, helping stakeholders make data-driven decisions on infrastructure investment and expansion.

## Key Questions
1. How has the availability of public vs. private EV charging infrastructure evolved over the last decade?
2. What trends can be observed in the sales of electric vehicles over the same time period?
3. Is there a correlation between the increase in charging ports and EV sales growth?

## Tools and Techniques
- **Data Wrangling**: Clean and preprocess the data for analysis.
- **Visualization**: Create time series plots to show the growth of EV charging infrastructure and sales over time.
- **Statistical Analysis**: Perform correlation analysis to explore relationships between charging infrastructure and EV sales.
- **Machine Learning** (optional): Build predictive models to forecast future trends in EV infrastructure and sales.

