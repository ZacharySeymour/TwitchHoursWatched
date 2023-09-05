# TwitchHoursWatched
This program analyzes a Twitch dataset and predicts the amount of hours watched on Twitch and analyzes how average viewers, number of streamers, game title, and other independent variables impact hours watched. Conducted regression analysis on dataset and used r-sqaured, RMSE, and MAE to measure performance. 

## How to run: 

Here are the steps to run Jupyter notebook cells in command line:

1. Open the Jupyter notebook you want to run in command line.
2. In the Jupyter notebook interface, click on the File menu and select Download as > Notebook (.ipynb).
3. Save the notebook file in a directory of your choice.
4. Open a command line interface (CLI) and navigate to the directory where you saved the notebook file.
5. Run the following command:

         - jupyter nbconvert --to script my_notebook.ipynb


         Replace my_notebook.ipynb with the name of your notebook file. This command will convert the notebook to a Python script.

7. After the conversion is complete, you can run the Python script using the following command:

        - python my_notebook.py


         Replace my_notebook.py with the name of the Python script generated by nbconvert.

8. The Python script will execute the code cells in the Jupyter notebook in the order they appear in the notebook.

# Data: 
Includes Top Twitch games from 2016 - 2023 and associated metrics.  
You can download the dataset from here: 
Source: https://www.kaggle.com/datasets/rankirsh/evolution-of-top-games-on-twitch?select=Twitch_game_data.csv

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.
