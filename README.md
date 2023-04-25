# Predicting Corn Prices
A study on predicting corn future prices based on weather and other commodity data. 

Created as the term project for [ECON 323: Quantitative Economic Modelling](https://courses.students.ubc.ca/cs/courseschedule?pname=subjarea&tname=subj-course&dept=ECON&course=323). The final deliverable is located in [`src/final_project.ipynb`](https://github.com/PrayusShrestha/crop-price-prediction/blob/master/src/final_project.ipynb). The data used is stored as CSV files under the `data/` directory. These were scraped from commodity and financial data APIs; code for this is in  [`src/data_scraper.ipynb`](https://github.com/PrayusShrestha/crop-price-prediction/blob/master/src/data_scraper.ipynb). 

## Background

The agriculture commodity market is an important part of the economic system. The futures market helps farmers by providing liquidity, price guidance and the ability to manage market price fluctuations. Traders provide this liquidity and seek to profit from fluctuations in the market but are faced with incomplete information. As identified by [Zhou et. al (2022)](https://ieeexplore.ieee.org/document/9898176), futures prices depend on various factors and can be affected by shocks to production levels and changes in policy decisions. As such, solely considering historical price as the single input factor is insufficient to predict commodity prices considering market volatility. This project aims to apply machine-learning methods to measure the influence of weather data on corn futures prices in the U.S. 

## ML Models 
We used 3 Neural Nets 
1. Multilayer perceptron (MLP)
2. Standard Recurrent Neural Network (RNN) with an Adam optimizer and L2 Regularization
3. Gated recurrent units (GRU) with an Adam optimizer and L2 Regularization

## Tech Stack 
The analysis and report was made in Jupyter notebooks, using Python along with libraries such as pandas, scikit-learn, PyTorch, among others. 




