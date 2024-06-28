# Analysis of Professional CS:GO Matches

This Jupyter Notebook contains an analysis of professional tier-1 CS:GO matches. The goal of the analysis is to explore various aspects of the game, such as popular maps, win/loss ratios of teams, and other key metrics.


Here, we perform exploratory data analysis (EDA) to uncover patterns and insights from the data. We analyze various metrics such as:

- Team victory depending on wins in specific rounds
- Team win rate
- Teams that most often made a comeback and won in the second half
- Whether starting on the defensive side leads to more wins
- Correlation between the number of games a team plays and their win rate
- Overall player statistics
- Correlation between the number of games a player plays and their median KD ratio
- Best players based on performance metrics
- 
### Used Files from Data source: [[CS:GO Professional Matches](https://www.kaggle.com/datasets/mateusdmachado/csgo-professional-matches)]:

- `Results.csv`: Map scores and team rankings
- `Economy.csv`: Round start equipment value for all rounds played
- `Players.csv`: Individual performances of players on each map

## How to Run the Notebook

To run the notebook, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/csgo-matches-analysis.git
    ```
2. Navigate to the project directory:
    ```sh
    cd csgo-matches-analysis
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
4. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```
5. Open the `csgo_matches_analysis.ipynb` notebook and run the cells.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- seaborn
- scipy

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.MIT) file for details.





