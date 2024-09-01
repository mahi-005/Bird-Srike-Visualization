# Bird Strikes Data Analysis

This project analyzes data from bird strikes on aircraft, providing insights into patterns, trends, and impacts on aviation. The analysis includes visualizations and statistics to help understand various aspects of bird strikes, such as the number of strikes over time, the costs incurred, and the altitudes at which strikes occur.

## Table of Contents

- [Introduction](#introduction)
- [Data Description](#data-description)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)
  - [Number of Bird Strikes](#number-of-bird-strikes)
  - [Airlines and Airports](#airlines-and-airports)
  - [Costs Incurred](#costs-incurred)
  - [Time of Day and Altitude](#time-of-day-and-altitude)
  - [Phase of Flight](#phase-of-flight)
  - [Effect of Bird Strikes](#effect-of-bird-strikes)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction

This project provides an exploratory data analysis (EDA) of bird strikes on aircraft, using data sourced from the U.S. Bird Strike Committee. The goal is to identify patterns and trends in bird strike incidents and to assess the impact on aviation safety and costs.

## Data Description

The dataset contains 25,558 records with 26 features each, including:

- *Record ID*: Unique identifier for each record.
- *Aircraft Type*: Type of the aircraft involved.
- *Airport Name*: Name of the airport where the incident occurred.
- *Altitude Bin*: Altitude at which the strike occurred.
- *Wildlife Species*: Species of wildlife involved in the strike.
- *Cost Total*: Total cost incurred due to the strike.
- *Flight Date*: Date and time of the incident.
- *Effect Impact to Flight*: Impact of the strike on the flight.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Packages: NumPy, Pandas, Matplotlib, Seaborn

## Installation

1. Clone the repository:
   bash
   git clone https://github.com/yourusername/bird-strikes-analysis.git
   
2. Navigate to the project directory:
   bash
   cd bird-strikes-analysis
   
3. Install the required packages:
   bash
   pip install -r requirements.txt
   

## Usage

1. Open the Jupyter Notebook in your preferred environment:
   bash
   jupyter notebook Bird_Strikes_Analysis.ipynb
   
2. Run the cells sequentially to perform the data analysis.

## Analysis

### Number of Bird Strikes

- *Bar Chart*: Number of bird strikes by year.
- *Line Graph*: Number of bird strikes by month.

### Airlines and Airports

- *Top Airlines*: Bar chart and pie chart showing the top 10 US airlines with the most bird strikes.
- *Top Airports*: Bar chart of the top 50 airports with the most bird strikes.

### Costs Incurred

- *Line and Bar Graphs*: Yearly cost incurred due to bird strikes.

### Time of Day and Altitude

- *Histogram*: Frequency of bird strikes by hour of the day.
- *Box Plot and Histogram*: Altitude of aeroplanes at the time of strike.

### Phase of Flight

- *Pie Chart and Bar Chart*: Distribution and number of bird strikes in different phases of flight.

### Effect of Bird Strikes

- *Stacked Bar Chart and Pie Chart*: Impact of bird strikes on flights.
- *Scatter Plot and Heatmap*: Altitude of strike vs. severity of impact.
- *Count Plot*: Relation between prior warning and impact of strike.

## Conclusion

This analysis provides valuable insights into the frequency, timing, and impact of bird strikes on aircraft. The findings can help aviation authorities and airlines implement better preventive measures and minimize the risks and costs associated with bird strikes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
