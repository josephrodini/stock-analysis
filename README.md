# VBA Challenge

This project constitutes the Module 2 Challenge for the Data Analytics and Visualization Boot Camp.

## Overview of Project

### Purpose

A good friend, Steve, is helping his parents evaluate green energy stocks. In particular, they have invested heavily in DAQO New Energy Corp, although Steve also has data for 11 other stocks over the 2017 and 2018 years. Steve wants to present his parents with information about the stocks' total daily volume and return percentage so they can choose the best stocks to invest in. We are helping Steve by creating a VBA script that will run these analyses for him.

## Analysis and Challenges

A VBA script called "AllStocksAnalysisRefactored" was created in order to run an analysis of the 11 green energy stocks. Specifically, code was written in order to calculate the stocks' total daily volume and return percentage. This script is a refactored coding of an earlier attempt to analyze the stock data, so we expect it to be more succinct and to run faster than the earlier iteration.

No major challenges were encountered during these analyses. If the data had been incomplete or if the data had been haphazardly organized within the data set, analyses would have proven to have been more difficult.

## Results

### Comparison of stock performances

See [a screenshot of the 2017 and 2018 stock performances](https://github.com/josephrodini/stock-analysis/blob/main/VBA_Challenge_compare.png). We can draw a few conclusions here. First, 2017 was a much kinder year for green energy stocks as 11 of the 12 returned positively, while in 2018 only two of the 12 did so. While we were skeptical of DQ's negative return in 2018, it did much better in 2017. However, the volume traded in 2017 was much lower than in 2018. 

### Execution times of the scripts

The original code [took over a second to run for both years](https://github.com/josephrodini/stock-analysis/blob/main/VBA_Challenge_notRefactoredRunTimes.png). The refactored code was faster for [both 2017] (https://github.com/josephrodini/stock-analysis/blob/main/VBA_Challenge_2017.png) [and 2018] (https://github.com/josephrodini/stock-analysis/blob/main/VBA_Challenge_2018.png). The key difference was the creation of a ticker index that iterated through all the arrays. 

### Limitations

Steve might want to consider comparing green data stocks to other fuel sourced stocks in order to see trends across different industries. He might also want more recent stock data to see more recent trends.
