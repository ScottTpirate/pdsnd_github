# US Bikeshare Data Analysis

Explore bike share usage patterns across three major cities in the United States—Chicago, New York City, and Washington, DC—using Python. This project is part of a programming exercise designed to demonstrate the ability to use Python to import data, handle user input, and calculate statistical results.

## Project Description

This project analyzes bikeshare data to uncover usage patterns and user statistics. It includes functionalities to filter data by city, month, and day; calculate descriptive statistics for travel times, station popularity, and user demographics; and allow the user to view raw data upon request.

## Datasets

The datasets include randomly selected data for the first six months of 2017 from:
- Chicago
- New York City
- Washington, DC

Each dataset contains the same core six columns:
- Start Time
- End Time
- Trip Duration (in seconds)
- Start Station
- End Station
- User Type (Subscriber or Customer)

Additionally, the Chicago and New York City files also contain the following two columns:
- Gender
- Birth Year

## Files

- `chicago.csv`
- `new_york_city.csv`
- `washington.csv`
- `bikeshare.py` (Python script)

## Requirements

- Python 3.x
- Pandas library
- NumPy library
  
## Installation

To set up your local environment to run the script, follow these steps:

- Install Python 3.x from the official website or using your package manager.
- Install required Python packages: `pip install pandas numpy`


## Features

- **Filter by City, Month, and Day**: Choose the data to analyze by specifying the city, the month, and the day of the week.
- **Statistical Calculations**: Calculate and display statistics regarding the most common months, days, and start hours for bike rides, the most popular stations, trip duration, and user information like the breakdown of user types, genders, and birth years (where available).
- **View Raw Data**: Users can opt to view 5 lines of raw data repeatedly until they choose to stop.

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change. Please ensure to update tests as appropriate.

## License

Distributed under the MIT License. See `LICENSE` for more information.

---
