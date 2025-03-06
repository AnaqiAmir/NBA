# NBA Games Prediction 🏀

## Overview 🔎
This project predicts the winners of NBA games based on the statistics of each team's previous performances.

## Cloning the Repository 🗄️
Clone the repository to your local machine using the following command:
```sh
git clone https://github.com/AnaqiAmir/NBA.git
cd your-repo
```

## Installing Dependencies 📲
You can install the required dependencies using either `pip` or `conda`.

### Using `pip`

Ensure you have Python installed, then run:

```sh
pip install -r requirements.txt
```

### Using `conda`

If you prefer to use `conda`, create a new environment and install dependencies with:

```sh
conda create --name <env_name> python=3.11
conda activate <env_name>
conda install --yes --file requirements.txt
```

## Files 📄
- `get_data.ipynb`: Get data through webscraping
- `parse_data.ipynb`: Process raw data in html files into readable csv format
- `analysis.ipynb`: Exploratory data analysis on the processed data
- `prediction.ipynb`: Data processing and model building

## Folders 📁
- `data/`: Contains game data of all NBA games from the 2019-2020 season to the 2023-2024 season.

## Tableau 📊
Please check out my interactive Tableau dashboard that visualizes the performance of individual teams [here](https://public.tableau.com/app/profile/anaqi.amir/viz/NBA_17222038331080/SeasonStatistics).

## Inspiration 💡
The idea for this project and the starter code (`get_data.ipynb`,`parse_data.ipynb`) was inspired by [DataQuest](https://github.com/dataquestio/project-walkthroughs/tree/master/nba_games)
