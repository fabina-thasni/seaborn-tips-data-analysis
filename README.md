# seaborn-tips-data-analysis
## INTRODUCTION

Seaborn is a powerful Python visualization library built on top of Matplotlib, providing a high-level interface for drawing attractive and informative statistical graphics.

Seaborn simplifies the process of creating complex visualizations and is particularly well-suited for visualizing data with relationships, distributions, and categories.

And integrates with the functionality provided by Pandas DataFrames.
## Install Seaborn.
* If you have Python and PIP already installed on a system, install it using this command:

C:\Users\Your Name>pip install seaborn

* If you use Jupyter, install Seaborn using this command:

C:\Users\Your Name>!pip install seaborn
## Import Seaborn
* Import the Seaborn module in your code using the following statement:

import seaborn as sns

## Explanation:
* Heatmap: Displays matrix data with color intensities representing values.
* Scatter Plot: Shows how two continuous variables relate to each other.
* Line Plot: Illustrates trends over a continuous variable.
* Bar Plot: Compares average values of a numerical variable across categories.
* Box Plot: Visualizes the distribution and outliers of a numerical variable by category.
* Violin Plot: Combines box plot features with a density plot to show the distribution of data.
* Pair Plot: Provides a grid of scatter plots and histograms to explore relationships between multiple variables.
* Count Plot: Shows the frequency of observations within each category.
* Joint Plot: Combines scatter plots with histograms or KDE plots for detailed relationships between two variables.
* Facet Grid: Creates multiple plots for different subsets of the data, facilitating comparison across categories.

### Tips Dataset
The Tips dataset contains information about tips received by waitstaff in a restaurant.

### Features and Characteristics
* total_bill: Total bill amount (numerical)

* tip: Tip amount (numerical)

* sex: Gender of the person paying the bill (categorical)

* smoker: Whether the person is a smoker (categorical)

* day: Day of the week (categorical)

* time: Time of day (Lunch/Dinner) (categorical)

* size: Size of the party (numerical)

### Information of the dataset
The tips dataset has 7 columns (features) and 244 rows (observations,samples).

* Numerical columns are:

1.total_bill (float) - the amount of the total bill

2.tip (float) - the amount of the tip paid on the bill

3.size (int) - the number of total people served

* Categorical columns are:
1.sex (Male/Female) - the gender of the person who paid the bill

2.smoker (Yes/No) - whether or not the person who paid the bill is a smoker

3.day (Thur/Fri/Sat/Sun) - the day when the person paid the bill

4.time (Lunch/Dinner) - the time of the day i.e. lunch or dinner

* There is no missing values
