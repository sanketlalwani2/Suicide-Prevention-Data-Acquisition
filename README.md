# Suicide Prevention Data Acquisition Project

## Overview
This project analyzes suicide data by country, gender, and age group, using datasets related to suicide rates and population statistics. The analysis is performed using Python, primarily leveraging pandas and numpy libraries for data manipulation and analysis.

## Project Structure
- `Suicide_project.ipynb`: Jupyter Notebook containing the code for data import, processing, and analysis.
- `data/`: Directory containing the datasets used in this project.
  - `Suicide.csv`: Dataset containing suicide rates by country, gender, and age group.
  - `Population.csv`: Dataset containing population statistics by country for multiple years.
  - `Human Resourses Data.csv`: Additional dataset used in the project.

## Datasets
### Suicide Dataset
The suicide dataset includes the following columns:
- `Country`: Name of the country
- `Gender`: Gender (Both sexes, Male, Female)
- `85+ years`, `75-84 years`, `65-74 years`, `55-64 years`, `45-54 years`, `35-44 years`, `25-34 years`, `15-24 years`: Suicide rates for different age groups

### Population Dataset
The population dataset includes the following columns:
- `cca2`: Country code
- `country`: Country name
- `pop2022`, `pop2021`, `pop2020`, `pop2050`, `pop2030`, `pop2015`, `pop2010`, `pop2000`, `pop1990`, `pop1980`, `pop1970`: Population counts for different years
- `area`, `landAreaKm`, `density`: Area and population density
- `GrowthRate`, `WorldPercentage`, `rank`: Growth rate, world percentage, and rank of the population

## Getting Started
### Prerequisites
- Python 3.x
- Jupyter Notebook
- pandas
- numpy

### Installation
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required Python packages:
   ```bash
   pip install pandas numpy
4. Place the datasets in the data/ directory.

## Running the Analysis
1. Open `Suicide_project.ipynb` in Jupyter Notebook.
2. Run the notebook cells sequentially to import the datasets, process the data, and perform the analysis.

## Data Processing
- The project includes code to import and preprocess the datasets.
- The suicide dataset is filtered to remove unnecessary rows and reset the index.
- The population dataset is processed to compute the population for 2019 using the growth rate and to retain only relevant columns.

## Analysis
- The analysis involves merging the suicide and population datasets.
- Various statistical analyses and visualizations are performed to explore the data and draw insights.

## Results
- The project provides insights into the suicide rates across different countries, genders, and age groups, as well as their correlation with population statistics.

