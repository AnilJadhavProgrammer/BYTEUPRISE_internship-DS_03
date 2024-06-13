# Accident Data Analysis

This project performs exploratory data analysis (EDA) on it. The dataset includes various attributes related to accidents, such as location, weather conditions, road conditions, severity, and contributing factors. The analysis includes visualizing accident hotspots, distributions of weather and road conditions, and other relevant insights.

## Table of Contents

- [Project Overview](#project-overview)
- [Project Highlight](#project-highlight)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Project Overview

The goal of this project is to analyze it to uncover patterns and insights. This can help in understanding common factors contributing to accidents and identifying potential areas for improving road safety.
This project generates safety recommendations based on the analysis of a synthetic dataset of road accidents. By examining various conditions such as weather, road, time of day, and contributing factors, the function provides actionable insights to improve road safety.


# Project Highlights
- **Exploratory Data Analysis (EDA):** Analyzed data to identify patterns and high-risk conditions.
- **Safety Recommendations:** Generated recommendations to mitigate identified risks and improve road safety.

## Dataset

The synthetic dataset includes the following columns:

- `Date`: Date of the accident
- `Time`: Time of the accident
- `Latitude`: Latitude of the accident location
- `Longitude`: Longitude of the accident location
- `City`: City where the accident occurred
- `State`: State where the accident occurred
- `Weather_Condition`: Weather condition at the time of the accident
- `Road_Condition`: Road condition at the time of the accident
- `Severity`: Severity of the accident (Minor, Major, Fatal)
- `Contributing_Factor`: Contributing factor to the accident (Speeding, Alcohol, Distracted Driving, Weather)
- `Traffic_Condition`: Traffic condition at the time of the accident (Light, Moderate, Heavy)
- `Vehicle_Type`: Type of vehicle involved in the accident (Car, Truck, Motorcycle, Bicycle)
- `Age`: Age of the driver
- `Gender`: Gender of the driver

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```sh
     https://github.com/AnilJadhavProgrammer/BYTEUPRISE_internship-DS_03

    ```

2. **Install the required dependencies:**
    Make sure you have Python installed. Then, install the required libraries using pip:
    ```sh
    pip install pandas matplotlib seaborn faker
    ```

## Usage

2. **Perform Data Analysis:**
    Run the analysis script to visualize and analyze the data:
    ```sh
    python analyze_data.py
    ```
    
### `analyze_data.py`

This script loads the dataset and performs exploratory data analysis (EDA), generating various plots to visualize the data.

## Results

The analysis includes the following visualizations:
- Accident hotspots on a geographical map
- Distribution of accidents by weather condition
- Distribution of accidents by road condition
- Distribution of accidents by time of day
- Contributing factors to accidents

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your improvements.

