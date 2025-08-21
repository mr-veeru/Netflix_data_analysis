# Netflix Data Analysis

A comprehensive data analysis project exploring Netflix's content library using Python, Pandas, and visualization libraries.

## 📊 Project Overview

This project analyzes Netflix's content dataset to uncover insights about:

- Content distribution (Movies vs TV Shows)
- Release patterns and trends
- Audience ratings and demographics
- Content duration analysis
- Seasonal and temporal patterns

## 📁 Project Structure

```
Netflix_data_analysis-main/
├── netflix_data_analysis.ipynb    # Main analysis notebook
├── netflix_titles.csv             # Netflix dataset
└── README.md                      # This file
```

## 🗃️ Dataset Information

The analysis uses the `netflix_titles.csv` dataset containing **8,807 Netflix titles** with the following attributes:

| Column         | Description                                    | Data Type |
| -------------- | ---------------------------------------------- | --------- |
| `show_id`      | Unique ID for every Movie/TV Show              | Object    |
| `type`         | Identifier - Movie or TV Show                  | Category  |
| `title`        | Title of the Movie/TV Show                     | Object    |
| `director`     | Director of the Movie                          | Object    |
| `cast`         | Actors involved in the movie/show              | Object    |
| `country`      | Country where the movie/show was produced      | Object    |
| `date_added`   | Date it was added on Netflix                   | Datetime  |
| `release_year` | Actual Release year of the movie/show          | Integer   |
| `rating`       | TV Rating of the movie/show                    | Category  |
| `duration`     | Total Duration in minutes or number of seasons | Object    |
| `listed_in`    | Genre                                          | Object    |
| `description`  | The summary description                        | Object    |

## 🛠️ Setup and Installation

### Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab

### Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Running the Analysis

1. Clone or download this repository
2. Ensure `netflix_titles.csv` is in the same directory as the notebook
3. Open `netflix_data_analysis.ipynb` in Jupyter Notebook
4. Run all cells to execute the complete analysis

## 📈 Key Findings

### Content Distribution

- **Movies dominate**: Significantly more movies than TV shows in Netflix's library
- **Growth trend**: Content addition increased dramatically after 2015
- **COVID impact**: Notable drop in content addition after 2019

### Temporal Patterns

- **Peak months**: October, November, and December see the most content additions
- **Weekday preference**: Friday is the most popular day for content releases
- **TV Show timing**: TV shows are more likely to be released on Fridays

### Duration Analysis

- **Movie duration**: Most movies are around 100 minutes, with a secondary peak at 25 minutes (short films)
- **TV Show seasons**: Most TV shows have 1-2 seasons, with a significant drop-off after season 1

### Audience Demographics

- **Adult content**: Most common content type on Netflix
- **Rating distribution**: Adult and Teen content dominate the platform
- **Movie vs Show**: More adult movies compared to adult TV shows

## 📊 Visualizations Included

The analysis includes various visualizations:

- Bar charts for content type distribution
- Line plots for yearly content addition trends
- Heatmaps for monthly/yearly content patterns
- Histograms and box plots for duration analysis
- Count plots for audience ratings and weekday patterns

## 🔧 Data Preprocessing

The analysis includes comprehensive data cleaning:

- Handling missing values in director, cast, and country columns
- Converting date_added to datetime format
- Creating derived features (year_added, month_added, day_added)
- Fixing data inconsistencies in rating and duration columns

## 📝 Analysis Sections

1. **Data Loading and Exploration**

   - Dataset overview and basic statistics
   - Missing value analysis

2. **Data Cleaning and Preprocessing**

   - Handling missing values
   - Data type conversions
   - Feature engineering

3. **Content Type Analysis**

   - Movies vs TV Shows distribution
   - Yearly trends in content addition

4. **Temporal Analysis**

   - Monthly and weekly patterns
   - Seasonal trends

5. **Duration and Rating Analysis**
   - Movie duration distributions
   - TV show season patterns
   - Audience rating demographics

---

**Note**: This analysis is based on a snapshot of Netflix's content library. The dataset may not reflect current Netflix offerings.
