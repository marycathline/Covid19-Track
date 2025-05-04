# COVID-19 Data Analysis - Visualizations

This project performs an analysis of COVID-19 data across multiple continents, focusing on total cases, deaths, vaccinations, and daily new cases. The dataset used for this analysis is from the "Our World in Data" COVID-19 dataset.

## Project Overview

This project provides visualizations that summarize the key statistics of COVID-19 for the continents of Africa, Asia, and Europe, and presents various types of charts:
- Line charts showing the total number of COVID-19 cases over time.
- Bar charts displaying the total number of deaths by continent.
- Pie charts visualizing the distribution of total vaccinations.
- Histograms showing the distribution of daily new cases.
- Scatter plots comparing total cases and total deaths by continent.

## Setup Instructions

### Prerequisites
To run this project, you need the following Python libraries installed:

- `pandas`: For data manipulation and analysis.
- `matplotlib`: For static plotting.
- `seaborn`: For enhanced data visualization.
- `plotly`: For interactive visualizations (optional but recommended).
  
You can install the necessary dependencies using `pip`:

```bash
pip install pandas matplotlib seaborn plotly

Running the Project
Download the Dataset
Ensure that you have the owid-covid-data.csv file in your project directory. You can download the dataset from Our World in Data.
👉 https://covid.ourworldindata.org/data/owid-covid-data.csv

Run the Python Script
The main script is the Python file that loads the dataset and generates visualizations. You can run it by executing the script in your terminal or using an IDE.

bash
python covid19-Track.py

This will generate the following plots:

Line Chart: Total COVID-19 cases over time for each selected continent.

Bar Chart: Total COVID-19 deaths for each continent.

Pie Chart: Distribution of total vaccinations across the selected continents.

Histogram: Distribution of daily new cases for the first continent.

Scatter Plot: Comparison of total cases and total deaths by continent.

Files in the Project
covid_analysis.py: The main script that loads the dataset, processes the data, and generates visualizations.

owid-covid-data.csv: The COVID-19 dataset (make sure this file is in the project directory).

Data Sources
The dataset used in this project is from Our World in Data:

GitHub Repository: Covid19-Track

The dataset includes global COVID-19 statistics, such as:

Total cases and deaths

New cases and deaths per day

Vaccination statistics

Population data

Observations
Europe has the highest cumulative cases and deaths among the selected continents.

Africa's COVID-19 numbers are relatively lower, possibly due to underreporting or lower testing.

Asia has had significant vaccination rollouts across many countries.

Acknowledgments
The dataset is sourced from Our World in Data.

The visualizations are created using matplotlib, seaborn, and plotly.
