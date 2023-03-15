# Exoplanets
Objective: perform aggregations on the planets dataset.
1) Open the Dataset
Open a Jupyter notebook and download the Planets dataset via the Seaborn package:

Remove rows with null values. How many rows are left?

2) Aggregations
Experiment with finding the mean, median and mode of some of the columns. Try to do it mathematically in the code as well as using .mean() etc.
Present the total number of items, mean, std, min, 25%, 50%, 75% and max values for each of the columns in a table. Is there an efficient way to do this?
3) Group By
Compare the average orbital periods of the different detection methods. What average would be best to give the best representation. 
Now, count the discovered planets by both method and decade. The count of planets discovered is given by the 'number' column, but the counts will need to be grouped by decade. This should take some thought. As a starting point, come up with a 'decade' variable which finds the decade each planet should fall into using '//' division.
