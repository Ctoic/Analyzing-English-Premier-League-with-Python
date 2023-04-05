# English Premier League Match Data Analysis
This repository contains Python code for analyzing match data from the English Premier League during the 2018-2019 season. The code is designed to answer the following questions:

Which team received the most red cards during the season?
Does the number of red cards a team receives have an effect on its probability of winning a game?
What percentage of games resulted in a draw during the season?
# Data
The match data is stored in a CSV file called coccer_18-19.csv, which contains the following columns:

# Libraries
The following Python libraries are used in the code:

1. Pandas: used for reading and manipulating the match data CSV file
2. Scikit-learn: used for training a logistic regression model to predict the outcome of a game based on the number of red cards received by each team
3. Matplotlib: used for plotting a bar chart of the percentage of games that resulted in a draw

# Methods
The code in this repository consists of the following Python scripts:

red_cards.py: reads the match data CSV file, computes the total number of red cards received by each team during the season, and prints the team that received the most red cards.
red_cards_outcome.py: reads the match data CSV file, trains a logistic regression model to predict the outcome of a game based on the number of red cards received by each team, and prints the accuracy of the model.
draw_percentage.py: reads the match data CSV file, computes the percentage of games that resulted in a draw, and plots a bar chart of the results.
To run the code, simply navigate to the root directory of the repository and run the desired script using a Python interpreter:

      python red_cards.py
      python red_cards_outcome.py
      python draw_percentage.py
# Conclusion
This repository provides a simple example of how to analyze match data from the English Premier League using Python. The code can be easily modified to answer other questions about the data, such as which team scored the most goals during the season or which player received the most yellow cards.





