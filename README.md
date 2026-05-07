*Author:** Prajwal DC

### README: Critical Instructions for Execution
**1. Extract the Archive:** If you downloaded this submission as a `.zip` file, you MUST extract/unzip the entire folder first. The code will fail if run directly from inside a compressed preview window.
**2. Working Directory:** Ensure the following three CSV files are located in the exact same unzipped directory as this `.ipynb` file:
   * `Cleaned_Master_Dataset.csv` (Historical match data with EA FC 26 proxy ratings) This is a combination of dataset from this season           premier league data which can be found on (https://www.football-data.co.uk/englandm.php) and historical data from kaggle (https://www.kaggle.com/datasets/marcohuiii/english-premier-league-epl-match-data-2000-2025) where was later filtered down to premier league data from 2022/2024.
   * `Arsenal-players.csv` (Current roster data) Dataset Link: (https://www.ea.com/games/ea-sports-fc/ratings?gender=0&team=1&team=10)
   * `ManchesterCity-Players.csv` (Current roster data) Dataset Link: (https://www.ea.com/games/ea-sports-fc/ratings?gender=0&team=1&team=10)

**Objective:** This project utilizes EA FC 26 player ratings to solve the "Cold Start" problem for newly promoted or altered squads. It trains a Random Forest classifier on historical data and utilizes a custom Key Player Index (KPI) to simulate squad depth sensitivity for the 2025/2026 title race.
