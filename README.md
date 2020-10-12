# 401 Project 1: Predictability vs. Interpretability 

## Steps to Run Code: 

1. [Assemble Datasets](https://github.com/juliandavis7/401_Project1/blob/master/assemble_dataset.ipynb) 
    1. This reads in the big dataset and combines our external dataset, resulting in 1 main file: [iowa_mounth_county.csv](https://github.com/juliandavis7/401_Project1/blob/master/iowa_month_county.csv)
    
2. [Find Most Interpretive](https://github.com/juliandavis7/401_Project1/blob/master/find_most_interpretive.ipynb)
    1. This notebook reads in our final aggregated dataset
    2. This contains all our functions to run the regression 
    3. This performs our forward stepwise process to find the most interpretive model
    
3. [Find Most Predictive](https://github.com/juliandavis7/401_Project1/blob/master/find_most_predictive.ipynb)
    1. This performs our backward stepwise process to find the most predictive model

4. External Datasets
    1. [Income Data](https://github.com/juliandavis7/401_Project1/blob/master/income.csv) 
        1. [Source](https://data.iowa.gov/Economic-Statistics/Annual-Personal-Income-for-State-of-Iowa-by-County/st2k-2ti2): Iowa Income Data from 1997-2020 from State of Iowa 
    2. [Population Data](https://github.com/juliandavis7/401_Project1/blob/master/iowa_county.xlsx)
        1. [Source](https://www.census.gov/data/datasets/time-series/demo/popest/2010s-counties-total.html): Iowa Population by County for 2010-2019 from Census 
    3. [Election Data](https://github.com/juliandavis7/401_Project1/blob/master/iowa_election.csv)
        1. [Source](https://public.opendatasoft.com/explore/dataset/usa-2016-presidential-election-by-county/table/?disjunctive.state&refine.state=Iowa&sort=rep16_frac): Iowa Demographics by County for the 2016 Election from Opendatasoft
