# Walkability-Analysis

The project was undertaken originally as part of a Data Science university group project, done as a 2-person team. 

The objective of this assignment waas to develop a [walkability score](https://www.walkscore.com/how-it-works/) for Sydney neighborhoods based on factors like density, destinations, distance to transport, and additional data like cafes, cycling infrastructure, public transport connectivity, and greenery. Analyze the correlation between walkability scores, median income, and average monthly rent.

Pair programming was utilised to complete the programming aspect of this assignment. 

The main notebook file is `Walkability Analysis Assignment.ipynb`. The original datasets and an ERD are also contained in this repository. 

## Tech Stack
- Python: Utilised to perform the data analysis in a Jupyter notebook.
- Psycopg2 (PostgreSQL): Used to establish connections to the university's PostgreSQL database and to perform SQL queries in order to load and manipulate the data to perform analysis.
- Matplotlib & Seaborn: Used to generate the scatter plots to determine correlation scores between different variables.
- Pandas: used to load the data as data frames which made it easier to work with,
- Numpy: used to perform numerical and mathematical calculations.
- Shape: used to load in shape files (.shp). 
- Geopandas: used to generate map diagrams using the shape files. 
