# API Visualizations
Python GitHub Repositories Analysis
This project provides a Python script that interacts with the GitHub API to fetch and visualize information about the most-starred Python repositories. It includes two primary functionalities:
1. API Data Retrieval:
Uses the GitHub API to search for repositories written in Python and sorted by the number of stars.
Prints out key information about each repository, including the name, owner, star count, repository URL, creation date, last update date, and description.

2. Data Visualization:
Utilizes Plotly to create an interactive bar chart of the top Python repositories.
The chart displays the repository names (as clickable links), star counts, and additional details (owner and description) on hover.
The resulting plot is saved as an HTML file (python_repos.html), which can be opened in a web browser.

3. Usage
Install Required Libraries:
Ensure you have the necessary libraries installed. You can install them using pip

4. Run the Script:
Execute the Python script to make an API call to GitHub, retrieve repository data, and generate a visualization.
python script_name.py

5. Replace script_name.py with the name of your Python script file.

6. View Results:
The console will display information about the top Python repositories.
The visualization will be saved as python_repos.html. Open this file in your web browser to explore the interactive bar chart.

7. Files
script_name.py: The main Python script for fetching data and generating the plot.
python_repos.html: The interactive bar chart of the most-starred Pyth
