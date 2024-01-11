# KORRA-Projects
# [Project 1: Egypt VS saudi World Cup 2018 Data analysis](https://github.com/Jrkasem/AK_healtcare_data_portfolio/blob/main/Soccer%20Game%20data%20analysis%20.ipynb)
This GitHub project is an advanced football (soccer) match data analysis tool that utilizes Python for in-depth statistical and visual examination of match events. The core of this project lies in its integration with the statsbombpy library, which enables the retrieval of detailed match data from StatsBomb, a renowned data provider in the world of football analytics. The project is structured to efficiently process this data, focusing on a specific team's performance in a given match. It meticulously organizes and filters the data, preparing it for various types of analysis. This includes isolating events like shots, passes, fouls, and player-specific actions, which are crucial for understanding the dynamics of the match.

The visualization aspect of the project is where it truly stands out. Leveraging the mplsoccer library, the tool creates a series of intuitive and informative plots that bring the match data to life. These include pitch maps that illustrate shot locations and outcomes, differentiating between goals and missed shots with color-coded markers. It also visualizes passing networks, showcasing the direction and end locations of passes with clear, directed arrows. The project extends its capabilities to generate time-based event distributions, pie charts for shot outcomes, player influence metrics through bar charts, and heat maps depicting player movements and defensive actions. These visualizations are not only valuable for post-match analysis but also offer potential for real-time insights, making the tool an invaluable resource for coaches, analysts, and football enthusiasts who seek a deeper understanding of the game's nuances.


# [Project 2: France VS Argntina Final World Cup 2022 Passes and Shots Maps](https://github.com/Jrkasem/AK_healtcare_data_portfolio/blob/main/pass%20and%20shots%20maps%20ARG%20VS%20FRA%202022%20Wrld%20cup%20adjusted.ipynb)

The provided code is a Python script using the matplotlib, numpy, and mplsoccer libraries to visualize soccer match data, specifically focusing on shots and passes during a game. It consists of several blocks, each with a specific function:

Data Loading and Basic Shot Visualization:

The script begins by importing necessary libraries for data handling and visualization (matplotlib, numpy, mplsoccer).
It uses Sbopen from mplsoccer to load event data for a specific match identified by its ID 3869685.
It extracts shots from the event data and creates a Pitch object to visualize these shots.
The script then loops through each shot, plotting them on the pitch with different characteristics (color, transparency) based on the team and whether the shot resulted in a goal.
A title is set for the figure, and the plot is displayed.
Advanced Shot Visualization with Grid Layout:

The script then creates another pitch visualization, this time using a grid layout.
It filters the shots for each team (Argentina and France) and plots them with different characteristics.
The coordinates are adjusted for one of the teams to reflect their actual positions on the pitch.
A title is set, and the visualization is displayed.
Vertical Pitch Visualization for One Team:

A vertical half-pitch visualization is created for Argentina’s shots against France.
All shots are plotted with specific characteristics and the figure is titled and displayed.
Pass Visualization for a Specific Player:

The script then focuses on visualizing passes made by a specific player, Lionel Messi, in the same match.
It filters the event data for passes made by Messi, and visualizes these as arrows on the pitch to show the direction and endpoint of each pass.
A title is set for the visualization, and it is displayed.
Grid Layout for Pass Visualization:

Similar to the shot visualization, a grid layout is used to visualize Messi’s passes.
Passes are plotted as arrows with starting and ending points.
The visualization is titled and displayed.
Pass Visualization for Multiple Players:

Finally, the script visualizes passes made by all Argentina players in a 4x4 grid layout.
Each subplot is dedicated to one player, showing their passes.
The script removes any extra, unused subplots.
A central title is added, and the visualizations are displayed.
Overall, this script demonstrates the use of data visualization techniques in Python to analyze and display soccer match data, particularly focusing on the actions (shots and passes) of players during a game.

# [Project 3: Advanced Soccer Analytics: Unveiling the England Women's Team's Performance through Data Visualization and Player Analysis](https://github.com/Jrkasem/AK_healtcare_data_portfolio/blob/main/Untitled6.ipynb)
In the initial phase, the script employs the Sbopen parser from the mplsoccer library to extract match data. It zeroes in on matches involving the England Women's team, compiling a list of match IDs for these games. This step is crucial as it lays the foundation for the subsequent detailed analysis. Following this, the script meticulously processes the event data for each match. A key focus here is the analysis of passes and shots made by the team. It filters and categorizes passes as "danger passes," which are essentially accurate, non-set piece passes made in the lead-up to shots. This categorization is significant as it helps in identifying passes that potentially contribute to scoring opportunities. Simultaneously, the script identifies shot events, using their timings to determine the relevant time windows for the danger passes. This dual analysis of passes and shots provides a comprehensive view of the team's offensive play.

The aggregation of danger pass data across all matches into a single DataFrame is a critical step that facilitates a holistic analysis. The script then transitions to the visualization phase, where it employs several techniques to represent the data graphically. The first visualization is a scatter plot on a soccer pitch diagram, which displays the locations of the danger passes. This visual representation is invaluable in understanding the spatial aspects of the team's play, highlighting areas on the pitch where goal-scoring opportunities are frequently created. Following this, a heatmap is generated to illustrate the density of danger passes across different pitch areas. Normalized by the number of games, this heatmap offers insights into the team's play patterns on a per-game basis.

The final part of the script focuses on individual player contributions. It simplifies player names to surnames and computes the number of danger passes per game for each player. This data is then presented in a bar chart, which effectively communicates the contribution of each player in creating dangerous situations on the field. This player-specific analysis not only accentuates individual performances but also aids in tactical planning and player development.






