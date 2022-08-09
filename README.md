# Open Source Datasets and Databases to Practice Data Science with

This is a list of databases and datasets that are all freely available and great for practicing R data manipulation and analysis. 
Before following any of these instructions, make sure you have the tidyverse installed by using this in R: 
```
install.packages("tidyverse")
```

## dslabs

[dslabs](https://cran.r-project.org/web/packages/dslabs/index.html)

There's 26 datasets already set up in R for you. 
To use the datasets in this package you need to do the following kind of steps: 
```r
# Install the package
install.packages("dslabs") 
library(dslabs)
```

For the dataset `admissions` for example, you first need to prep it with `data()` function and then you can call it as an object. 
```r
data(admissions)
admissions
```

## FiveThiryEight Data 

There's a variety of datasets available as CSVs. 

[Go to the GitHub](https://github.com/fivethirtyeight/data) 
When you find the dataset you are interested in, click on that folder and then click on the data file you are interested in. 
Then click `Raw`. 
Copy and paste the URL that that brings you to. 
For example, for the `airline-safety` dataset, the URL would look like this: 
```
https://raw.githubusercontent.com/fivethirtyeight/data/master/airline-safety/airline-safety.csv
```
Then you can use that URL in a read_csv function like this: 
```r
airline_safety <- readr::read_csv("https://raw.githubusercontent.com/fivethirtyeight/data/master/airline-safety/airline-safety.csv")
```

## Databases 


