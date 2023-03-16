# ipl-cricket-match-win-predictor

This is a Python-based IPL cricket match win predictor. The predictor uses machine learning algorithms to analyze past IPL match data and make predictions on the probability of a team winning a match.

## Requirements

To run this project, you need to have the following dependencies installed on your system:

- Python 3.x
- NumPy
- Pandas
- sklearn
- streamlit

## Installation

1. Clone or download the repository.

```bash
git clone https://github.com/AmreshSharma01/ipl-cricket-match-win-predictor.git
```

2. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

3. Run the project:

```bash
streamlit run app.py
```

## Usage

1. Run the project using the above command.
1. Enter the name of the teams playing the match.
1. Enter the venue of the match.
1. Enter the toss winner and the team that chose to bat/bowl first.
1. Enter the current score and wickets of the team batting first.
1. The program will output the predicted probability of winning the match of the team batting in second inning.

## How it works

The project uses a machine learning algorithm called logistic regression to analyze past IPL match data and make predictions on the probability of a team winning a match. The algorithm takes into account various factors such as the teams playing, the venue of the match, the toss winner, and the current score and wickets of the team batting first to make its prediction.

## Data

The project uses IPL match data from the years 2008 to 2020, which are available in the `matches.csv, deliveries.csv, teams.csv, Players.xlsx and teamwise_home_and_away.csv` files in the repository.

## Contributing

Contributions are always welcome!

If you would like to contribute to the project, feel free to fork the repository and submit a pull request.
