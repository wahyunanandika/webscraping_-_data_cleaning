# Basketball Data Processing Pipeline

This repository implements a pipeline to scrape, clean, merge, and process basketball data. It focuses on integrating team and player statistics, as well as advanced metrics, to help analyze NBA data in a structured and efficient way. The pipeline includes web scraping functionality to retrieve team data and prepares the data for further analysis, including merging it with player and advanced statistics.

## Table of Contents

1. [Description](#description)
2. [Requirements](#requirements)
3. [Getting Started](#getting-started)
4. [Functions](#functions)
5. [License](#license)

## Description

The Basketball Data Processing Pipeline aims to integrate data from multiple sources (team and player stats, and advanced metrics) into a unified dataset. 

### Key Features:
- **Web Scraping**: Scrapes team data from a specified URL to keep statistics up to date.
- **Data Cleaning**: Removes unnecessary columns, handles missing values, and standardizes data formats (e.g., renaming columns and fixing inconsistent naming conventions).
- **Data Merging**: Combines player stats with team data and advanced metrics based on shared attributes such as player name and team abbreviation.
- **Advanced Metrics**: Loads advanced player statistics, such as PER, TS%, and WS/48, to enrich the analysis of player performance.
- **Final Output**: Saves the cleaned and merged data into a CSV file for further analysis or use in machine learning models.

This pipeline is designed to streamline the data preprocessing phase of NBA analysis and can be adapted to include additional data sources or modifications based on project requirements.

## Requirements

Ensure you have the following Python libraries installed:

- `pandas`
- `requests`
- `beautifulsoup4`
- `selenium`

You can install them using pip:

```bash
pip install pandas requests beautifulsoup4 selenium
