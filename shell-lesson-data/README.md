# DataCapentry Repository

This repository contains data files, scripts, and analysis reports related to various data science and research projects.

## Repository Structure

```
.
├── north-pacific-gyre/
│   ├── NENE01729A.txt
│   ├── NENE01729B.txt
│   ├── NENE01736A.txt
│   ├── NENE01751A.txt
│   ├── NENE01751B.txt
│   ├── NENE01812A.txt
│   ├── NENE01843A.txt
│   ├── NENE01843B.txt
│   ├── NENE01971Z.txt
│   ├── NENE01978A.txt
│   ├── NENE01978B.txt
│   ├── NENE02018B.txt
│   ├── NENE02040A.txt
│   ├── NENE02040B.txt
│   ├── NENE02040Z.txt
│   ├── NENE02043A.txt
│   ├── NENE02043B.txt
│   ├── goodiff.sh
│   ├── goostats.sh
│   └── notes.text
├── gapminder_data.csv
├── gapminder_analysis_report.html
└── README.md
```

## Data Files

### North Pacific Gyre Data
The `north-pacific-gyre/` directory contains sample data files in text format:
- `NENE*.txt`: Sample data files from the North Pacific Gyre research
- Each file contains approximately 4KB of data

### Gapminder Dataset
- `gapminder_data.csv`: Global development statistics from the Gapminder Foundation
  - Contains 1,704 records covering years 1952-2007
  - Includes data on life expectancy, GDP per capita, and population
  - Covers 5 continents: Africa, Americas, Asia, Europe, Oceania

## Analysis Reports

### Gapminder Data Analysis Report
- [`gapminder_analysis_report.html`](gapminder_analysis_report.html): Comprehensive HTML analysis of the Gapminder dataset
  - Interactive statistics and visualizations
  - Life expectancy, GDP, and population trends
  - Regional analysis by continent
  - Top countries rankings for key indicators

## Scripts

The repository includes two shell scripts for data processing in the north-pacific-gyre directory:

### goostats.sh
A script to calculate basic statistics on the data files.

### goodiff.sh
A script to compare differences between data files.

## Usage

To use the scripts in the north-pacific-gyre directory:
```bash
./goostats.sh NENE01729A.txt
./goodiff.sh NENE01729A.txt NENE01729B.txt
```

Make sure the scripts are executable:
```bash
chmod +x goostats.sh goodiff.sh
```

To view the Gapminder analysis report, simply open `gapminder_analysis_report.html` in your web browser.

## Notes

The `notes.text` file in the north-pacific-gyre directory is available for any additional documentation or observations related to the data.## Recent Updates  
- Added comprehensive Gapminder data analysis (November 2026)  
- Generated interactive HTML report with statistical insights  
- Created documentation and changelog for tracking changes  
-  
## Files Modified/Added:  
- gapminder_data.csv: Global development statistics dataset  
- gapminder_analysis_report.html: Interactive HTML analysis report  
- README.md: Updated documentation (this file)  
- CHANGELOG.md: Tracking of recent changes  
-  
### Analysis Highlights:  
- Life expectancy trends across continents and time  
- GDP per capita analysis and correlations  
- Population growth patterns  
- Regional breakdowns and comparisons  
- Top performing countries in various metrics  
-  
---  
