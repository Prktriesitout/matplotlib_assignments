# matplotlib_assignments
Auto MPG Data Visualization with Matplotlib &amp; Pandas

This repository features a Jupyter/Google Colab notebook dedicated to exploring, cleaning, and visualizing the classic Auto MPG dataset using Python's Pandas and Matplotlib libraries.

📊 Key Features:
Data Cleaning: Handles missing values in the horsepower column dynamically using mean imputation.
Feature Engineering: Derives new features such as city_mileage for deeper analysis.
Interactive Visualizations:
Line Plots: Custom multi-axes and multi-subplot configurations demonstrating structural layouts in Matplotlib.
Box Plots: Side-by-side distributions comparing overall mileage against city mileage.
Bar Charts: Trend analysis of the total number of cars produced across different model years.
Histograms: Frequency distributions of engine horsepower.
Pie Charts: Percentage breakdowns of automobile origins (e.g., USA, Europe, Japan).
🛠️ Tech Stack:
Python (Pandas, NumPy, Matplotlib)
Tip: Before committing, you might want to fix the minor KeyError: 'Country' in the pie chart cell. In newer versions of pandas, .value_counts() returns a Series where the index contains the original values. When you run .reset_index(), the columns become origin (or whatever the column name was) and count instead of index and Count.
