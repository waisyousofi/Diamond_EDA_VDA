# [Project overview](https://github.com/waisyousofi/Diamond_EDA_VDA)

Diamond pricing involves a complex mechanism influenced by multiple factors such as carat, cut, color and specially price .
This project will analyze the correlation between these factors and depicts with visualizations,
overall a cleaned dataset with no missing values or messy data will be provided which is ready for the processes like model building or ML processes.
<hr>


# Description
- Format :A data frame with 53940 rows and 10 variables
- This dataset containing the prices and other attributes of almost 54,000 diamonds. The variables are as follows:
- price: price in US dollars (\$326--\$18,823)
- carat: weight of the diamond (0.2--5.01)
- cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- colour: diamond colour, from J (worst) to D (best)
- clarity: a measurement of how clear the diamond is (IF (best), VVS1, VVS2, VS1, VS2, SI1, SI2, I1 (worst) )
- popularity: popularity of this specs (Good, Fair, Poor)
- x: length in mm (0--10.74)
- y: width in mm (0--58.9)
- z: depth in mm (0--31.8)
- depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
- table: width of top of diamond relative to widest point (43--95)
<hr>

# Code and Resources Used

- Python Version: 3.8.5
- Packages or libraries: pandas, seaborn, numpy, matplotlib, sklearn, warnings
- data source: https://www.kaggle.com/shivam2503/diamonds, https://medium.com/swlh/exploratory-data-analysis-21bbf3887e28
<hr>

# Findings from VDA
- Correlation table of all the columns
- <img src="https://raw.githubusercontent.com/waisyousofi/Diamond_EDA_VDA/main/images/Figure%202021-04-19%20185547%20(31).png">
- since the price is a dependent variable, comparson between price and all other attributes which affect on it is visualized as:
- ![](/images/Figure%202021-04-19%20185547%20(29).png)
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(29).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(31).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(32).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(33).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(34).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(35).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(36).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(37).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(38).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(39).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(40).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(41).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(42).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(43).png">
- <img src="https://github.com/waisyousofi/Diamond_EDA_VDA/blob/main/images/Figure%202021-04-19%20185547%20(44).png">
