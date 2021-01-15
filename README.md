# BeerAnalysis 

created by * [Rick Fontenot]('https://github.com/rickfontenot/DS6306_Study1') * [Jason Herbaugh](https://github.com/jherbaugh) * [Joseph Lazarus](https://github.com/JoeLazarus)

## Purpose

The Client, "Budweiser," hired our team to conduct specific analysis and anticipated new questions of expanding market share.

## YouTube Video

* [Rick's Youtube Video](www.youtube.com) 
* [Jason's Youtube Video](www.youtube.com) 
* [Joe's Youtube Video](www.youtube.com)

## Presentations

* [Beer Analysis EDA Presentation](https://github.com/rickfontenot/DS6306_Study1/blob/main/Case%20Study%201%20EDA.ppt.zip) - Zip folder containing Power Point Presentation covering Exploratory Data Analysis Directed from Client.

* [Beer Analysis Final Presentation](https://github.com/rickfontenot/DS6306_Study1/blob/main/Budweiser%20Presentation.ppt.zip) - Power Point Presentation covering the questions of Interest from our EDA as well as additional insights.

## Data
The Data Sets

* ['Beers.csv']('https://github.com/rickfontenot/DS6306_Study1/blob/main/Beers.csv')  The US craft beers data set

* ['Breweries.csv']('https://github.com/rickfontenot/DS6306_Study1/blob/main/Breweries.csv') The US craft breweries data set

* ['NIH_per_capita.csv'](https://github.com/rickfontenot/DS6306_Study1/blob/main/NIH_per_capita.csv) - * [Source]('https://vinepair.com/articles/map-states-drink-beer-america-2020/') - Data from National Institute from Health regarding per capita alcohol consumption broken down by state

* ['NIH_total_consumption.csv'](GithubURL)  * [Source](https://vinepair.com/articles/map-states-drink-beer-america-2020/) - Data from National Institute from Health regarding total alcohol consumption broken down by state

['nst.est2019.csv'](https://github.com/rickfontenot/DS6306_Study1/blob/main/nst-est2019.csv) Source ('https://www.census.gov/data/datasets/time-series/demo/popest/2010s-state-total.html') Data from US Census estimations of state population 2019

## Analysis

1.   How many breweries are present in each state?

2.   Merge beer data with the breweries data. Print the first 6 observations and the last six observations to check the merged file.  (RMD only, this does not need to be included in the presentation or the deck.)

3.   Address the missing values in each column.

4.   Compute the median alcohol content and international bitterness unit for each state. Plot a bar chart to compare.

5.   Which state has the maximum alcoholic (ABV) beer? Which state has the most bitter (IBU) beer?

6.   Comment on the summary statistics and distribution of the ABV variable.

7.   Is there an apparent relationship between the bitterness of the beer and its alcoholic content? Draw a scatter plot.  Make your best judgment of a relationship and EXPLAIN your answer.

8.  Investigate the difference with respect to IBU and ABV between IPAs (India Pale Ales) and other types of Ale (any beer with “Ale” in its name other than IPA).  Using KNN classification to investigate this relationship.  Provide statistical evidence one way or the other. 

9.  Performed market analysis highlight under developed craft brew markets within the United States that have the greatest potential to gain market share. As well as potential demand for Budweiser Brewery Brewery Experience Sites. 

### Details 
The primary focus of this project is to display skill in each step of the **Data Science Process**; 
1. Define the Goal 
2. Get the Data 
3. Clean the Data
4. Enrich the Data
5. Find insights and visualize
6. Deploy Machine Learning
7. Iterate ∞

in order to **Interperate and Communicate** Findings with stake holders. 

Based on the analysis, Colorado and California are the top two states which have the most breweries. Colorado at number 1, with 47 breweries. 

### Addressing Missing Values
Data Scientists rarely work on perfect data and thus a large percentage of effort is devoted to steps 2 and 3. In our analysis of the beer data set we found 42% of the beers are missing IBU information. 2.6% are mising ABV information. We evaluated 3 methods to impute missing values. 

1. Impute based on Predicitive Mean Matching (PMM)
2. Replace missing values with mean of respective class of beer
3. Omitting NA values from our data set



## CodeBook

The [Codebook](https://github.com/rickfontenot/DS6306_Study1/blob/main/Case%20Study%201%20Codebook.docx) - Provides additional details regarding the session information of the environment.

## Contributing

Don't. Project End of Life is January 16, 2021

## Authors

* **Rick Fontenot** - **Jason Herbaugh** - **Joseph Lazarus**

## License
MIT License

Copyright (c) [2021] [Rick Fontento, Jason Herbaugh, Joseph Lazarus]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgements

* Special thanks to Stack Overflow and anyone else's code used in this project. 
