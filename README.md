## This directory contains the relevant Jupyter Notebooks for Project 2 -- Luther (linear regression and webscraping). 

```
#directory contents
1 TR_WEB_SCRAPING_BEAUTIFUL_SOUP_SCRAPE_3_LETTER_WORLDBANK.html.ipynb               
2.0 TR CLEAN DATA PROPER NaN ASSIGNMENT.ipynb                                       
2.1 TR NaN REMOVAL ALGORITHM.ipynb                                                  
2.3 TR NaN REMOVAL ALGORITHM TIPS METHOD .ipynb                                     
3 TR CLEANING DATA -- REMOVING BAD SCRAPES .ipynb                                   
4 TR LINEAR REGRESSION MODEL AND EVALUATION by BIC.ipynb                            
5 TR CROSS VALIDATION TEST.ipynb
6 TR APPENDIX-A Create Table with Three Letter Country Codes with Sub_Region .ipynb
7 TR APPENDIX-B 3-CODE COUTNRY NAME LIST.ipynb
README.md
Iimages
ongoing
pickles
```
The files are organized chronologically as I worked through the project. If a some resource path doesn't work, it is most likely because the file was moved into the ongoing/ directory during clean-up. Adding './ongoing/' to the path should fix it. 

The most interesting accomplishement in this project was the invention of an approach for automating cleaning dataframe of NaN cells. That work is contained in 2.0 - 2.3. It is not completely automated yet, but I think could be with more work. 

The Linear regression work could be improved further with regularization. I optimized my model features by minimizing BIC on all combinations of considered features. It produced an Adj-R^2 of 0.92, but was improved to 0.94 by np.log(feature) and np.power(feature, n) on specific features. And at that point I had to use my remaining time for presentation prep.  

