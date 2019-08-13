# VPI

The aim of this project is to present simple methods of webscraping. The following example therefore uses a web page whose static content is to be analyzed. The aim is to obtain the consumer price indices automatically from the Statistics Austria website and to plot the annual averages for an index. The following points are important for the implementation: 

1. Missing values are marked with a dot and must be converted to NA.
2. The decimal point is given by a comma and causes the values to be interpreted as text.
3. The table on the webpage has a table footer that explains the data, but does not belong to the data points. 

If you want to start an interactive code-session please click:  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/smalldatascience/VPI/master?filepath=VPI.ipynb)
## Input 
![picture of the source webpage](pictures/webpage_input.png?raw=true "Input")

## Output 
![output table](pictures/final_table.png?raw=true "Input")
![output graph](pictures/graph_KHPI.png?raw=true "Input")



