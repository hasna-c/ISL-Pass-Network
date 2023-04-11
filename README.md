# ISL Pass Network

This football pass network is a visual representation of the passing relationships between players on a football team in an ISL match between Kerala blasters Vs Hyderabad fc.Pass network used for analysts to develop game plans, identify strengths and weaknesses of a team, and evaluate player performance. They can also be used by broadcasters and journalists to provide insights and analysis for viewers and readers.



### Visualizing Kerala Blasters' Passes
Visualization of the passes made by Kerala Blasters that were not throw-ins during a football match against Hyderabad. The code uses the mplsoccer library to create a grid of 4x4 pitches, one for each player who made a pass, and plots arrows between the start and end coordinates of each pass.

1.Prepare a DataFrame of passes by Kerala Blasters that were not throw-ins.
2.Get the list of all players who made a pass.
3.Draw 4x4 pitches using the Pitch object from mplsoccer.
4.For each player who made a pass, plot the passes as arrows on the corresponding pitch.
5.Remove any empty pitches.
6.Set the title of the plot.

In a passing network, the players are represented by nodes or vertices, and the passes between them are represented by edges or lines. The width of the lines represents the number of passes between the players.
