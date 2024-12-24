# PRODIGY-_DS_task05
# Traffic Accident Analysis: Patterns of Road Conditions, Weather, and Time of Day

## Project Overview

This project focuses on analyzing traffic accident data to identify patterns related to road conditions, weather, and time of day. The goal is to uncover insights regarding the distribution of accident severity, the influence of weather conditions, and how the time of day impacts traffic incidents. The analysis also aims to visualize accident hotspots across different states in the United States.

## Dataset

The dataset used for this analysis is sourced from Kaggle:

- [US Accident Dataset](https://www.kaggle.com/code/harshalbhamare/us-accident-eda)

The dataset contains information on various traffic accidents across the United States, including factors such as severity levels, weather conditions, geographical locations (latitude and longitude), and time-related variables.

## Key Insights

### 1. Severity Levels Distribution

- A bar chart reveals the distribution of severity levels, with **severity level 2** (moderate incidents) dominating the dataset with approximately 95,000 cases, while **severity level 4** (severe incidents) is much rarer, with only 1,000-2,000 cases.
- The absence of severity levels 1 and 3 suggests they either don't exist in the classification system or no cases were recorded for these levels.

### 2. Weather-Related Features

- **Temperature (°F):** Roughly normal distribution centered around 50-60°F, spanning temperatures from -20°F to 90°F.
- **Visibility (mi):** A spike around the 10-mile mark, with lower frequencies at other distances, suggesting clear weather conditions are most common.
- **Wind Speed (mph):** Most wind speeds concentrated between 0-15 mph, with a sharp peak around 5-10 mph.
- **Distance (mi):** Most measurements fall within the 0-20 mile range, indicating local weather monitoring or reporting patterns.

### 3. Weather Conditions and Incident Severity

- **Fair weather** conditions (clear weather) dominate the dataset, showing a high number of incidents with severity level 2.
- **Cloudy** and **mostly cloudy** conditions show a decreasing trend in accident frequency.
- While more severe weather conditions (e.g., heavy rain, haze) result in fewer accidents, they don't significantly correlate with increased severity (level 4).

### 4. State Distribution

- **California** and **Florida** are the two states with the highest number of incidents, accounting for most of the recorded accidents in the dataset.
- Severity level 2 incidents dominate in these states, while severity level 4 remains low across all states.

### 5. Incident Location (Geographical Patterns)

- Incidents are most common along the **coasts**, especially in **California** and **Florida**, with a dense cluster of incidents along the Eastern Seaboard.
- **Urban areas** exhibit more incidents, while less populated central areas show fewer incidents.
- Severity level 2 incidents are the most common, with severity level 4 scattered across the U.S.

## Visualizations

1. **Severity Levels Distribution**: A bar chart showing the contrast between severity levels.
2. **Weather Conditions Distribution**: Histograms illustrating temperature, visibility, wind speed, and distance.
3. **Weather vs Severity**: A bar chart comparing weather conditions with accident severity.
4. **State vs Severity**: A bar chart showing incident counts across U.S. states.
5. **Geographical Distribution**: A scatter plot visualizing incident locations across the United States, highlighting accident hotspots.

## Conclusion

This analysis reveals that most traffic incidents are moderate in severity, with fair weather conditions being the most common. Weather conditions, while affecting the frequency of accidents, do not seem to correlate significantly with higher severity levels. Geographically, accidents are more common in urban and coastal regions, with California and Florida leading in incident counts.

## Future Work

- Explore additional features (e.g., road conditions, traffic volume) to gain a deeper understanding of accident severity.
- Implement machine learning models to predict accident severity based on weather, location, and time of day.
- Investigate time-of-day trends more comprehensively, including seasonal variations.

## Requirements

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
