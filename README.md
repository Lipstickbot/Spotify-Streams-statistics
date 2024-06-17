# Spotify-Streams-statistics
This code loads data from a CSV file, assuming the file is in the specified path, and then builds a bar chart for the "Spotify Streams" column. Here's a brief description of each step:

1. Importing libraries:
   - `pandas` for working with data in the form of a DataFrame.
   - `numpy` for working with numeric data.
   - `matplotlib.pyplot` for plotting.

2. Loading data from a CSV file into a DataFrame (`df`):
   - Path to file: `'C:\Users\vovot\Downloads\spotif\spoti2024.csv'`.
   - 'latin1' encoding is used.

3. Convert 'Spotify Streams' column to number format:
   - This is done to ensure that the data in this column is a number.

4. Sort DataFrame by 'Spotify Streams' column in descending order:
   - This creates a new DataFrame `sorted_df` sorted by number of Spotify plays.
5. Building a bar chart:
   - Uses DataFrame's `plot` method to plot the graph.
   - `kind='bar'` specifies the type of graph (bar chart).
   - Adding labels to axes and a graph title.

6. Displaying a graph using `plt.show()`.

If you have any questions about specific lines of code, don't hesitate to ask!
