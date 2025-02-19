# U.S. Migration Trends (2010-2022)

## Overview
This project analyzes U.S. state-to-state migration trends from 2010 to 2022, leveraging data from the U.S. Census Bureau. The dataset provides insights into population distribution, interstate movement, and individuals relocating from abroad. 

## Data Sources
The dataset consists of 12 Excel files, each representing migration data for a specific year, excluding 2020 (data not provided by the U.S. Census Bureau). These files contain structured migration statistics, including:
- The total population of each state.
- Number of residents who lived in the same house the previous year.
- Number of people who moved within the same state or from different states.
- Migration from abroad, including Puerto Rico, U.S. Island Areas, and foreign countries.

## Data Cleaning and Processing
The dataset required extensive cleaning and restructuring:
- Removed titles, comments, and MOE (Margin of Error) columns.
- Standardized column names for consistency.
- Merged data from all years into a single dataset.
- Reshaped the dataset into a long format to facilitate analysis.

## Output and Accessibility
The cleaned and processed dataset has been uploaded to Kaggle for public access. You can find it at:
[**Kaggle Dataset: Migration Flows Across U.S. States (2010–2022)**]([https://www.kaggle.com/](https://www.kaggle.com/datasets/ygebre1/migration-flows-across-u-s-states-20102022))

## Usage
This dataset can be used for:
- Analyzing migration patterns over time.
- Identifying states with the highest and lowest inbound/outbound migration.
- Studying the impact of external factors (economic shifts, policy changes) on migration trends.

## Repository Contents
- `us_migration_cleaning.ipynb` - Jupyter Notebook containing data cleaning, exploration, and visualization code.
- `migrations_2010_to_2022.csv` - The cleaned dataset in CSV format.
- `README.md` - Documentation of the project.

## License
This dataset and analysis are provided for educational and research purposes. Please credit the U.S. Census Bureau as the primary data source.
