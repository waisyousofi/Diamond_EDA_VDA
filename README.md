# [Project overview](https://github.com/waisyousofi/Diamond_EDA_VDA)

Diamond pricing involves a complex mechanism influenced by multiple factors such as carat, cut, color and specially price . </br>
This project will analyze the correlation between these factors and depicts with visualizations,
overall a cleaned dataset with no missing values or messy data will be provided which is ready for the processes like model building or ML processes.
<br>



# Description
- Format :A data frame with 53940 rows and 10 variables
- This dataset containing the prices and other attributes of almost 54,000 diamonds. The variables are as follows:<br>
- price: price in US dollars (\$326--\$18,823)</br>
- carat: weight of the diamond (0.2--5.01)</br>
- cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)</br>
- colour: diamond colour, from J (worst) to D (best)</br>
- clarity: a measurement of how clear the diamond is (IF (best), VVS1, VVS2, VS1, VS2, SI1, SI2, I1 (worst) )</br>
- popularity: popularity of this specs (Good, Fair, Poor)</br>
- x: length in mm (0--10.74)</br>
- y: width in mm (0--58.9)</br>
- z: depth in mm (0--31.8)</br>
- depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)</br>
- table: width of top of diamond relative to widest point (43--95)
<hr>

# Code and Resources Used

- Python Version: 3.8.5</br>
- Packages or libraries: pandas, seaborn, numpy, matplotlib, sklearn, warnings
- data source: </br>https://www.kaggle.com/shivam2503/diamonds, </br>https://medium.com/swlh/exploratory-data-analysis-21bbf3887e28

# Findings from VDA
- since the price is a dependent variable, comparson between price and all other attribute which affect on it is visualized as:
- ![alt text](image.jpg)
