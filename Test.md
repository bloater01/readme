# NBA Player Stats Analytics App

## Overview


This documentation provides a comprehensive overview of the NBA stats dataset for the years 1998 to 2002. Each attribute has been explained in detail to facilitate a better understanding of the dataset and its potential applications.NBA Stats Dataset Documentation (1998-2002)
Overview
This documentation provides an in-depth explanation of the attributes included in the NBA stats dataset from Kaggle, covering the years 1998 to 2002. The dataset contains information about various player statistics during this time period.

## Features

- **Yearly Player Stats:** View statistics for NBA players' performance basis for each year.
- **Select Specific Player** View in-depth individual player stats by selecting (click 2 lmb) the player of choice or using filter to find a specific player to view whether by position or year.
- **Data Visualization:** Utilizes scatterplots for visualizing player performance trends and patterns.
- **JSON Data Loading:** The app supports loading player data from a JSON file, allowing users to easily update and customize the dataset.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/nba-analytics-app.git
    ```

2. Install dependencies:

    ```bash
    cd nba-analytics-app
    npm install
    ```

3. Upload player data:

    - Prepare a JSON file with player statistics (e.g., `players_data.json`).
    - Upload the JSON file to the app.

## Usage

1. Run the app:

    ```bash
    npm start
    ```

2. Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

3. Explore player statistics and visualizations using the user-friendly interface.

## Why Scatterplots?

Scatterplots are chosen for their effectiveness in displaying the relationship between two variables. In the context of this project, scatterplots are employed to showcase the correlation between different player statistics, such as points scored, assists, and rebounds per game. This visual representation allows users to identify trends, outliers, and patterns, providing a deeper understanding of player performance over time.

## Contributing

If you'd like to contribute to the project, please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
