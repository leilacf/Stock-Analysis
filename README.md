# Stock-Analysis
Utilizing VBA to analyze stocks

# 1. Overview of project
  ## Purpose and Background
  The purpose of this project was to assist Steve, as the financial consultant of his parents, in creating a detailed investment portfolio where he could properly advise their financial decisions--based off of our stocks analysis. In having access to the data on stocks, time in years, and total volume, we were able to facilitate the analysis on the return on investment in 2017 and 2018, which served to aid in the understanding of future positive or negative projections of certain stocks.
  
  
  # 2. Results
  ## Analysis Description
  ###### Analysis of stock performance
  In terms of stock performance between 2017-2018, 50% of the 12 stocks analyzed reduced in their total daily volume. Volume is quite an important measure as its relationship with price, can indicate to analysts a particular price point that shows high active participation from the public (shown through increasing volume). This subsequent strength at a particular market price, can indicate a peak number of shares, recorded daily. In terms of the ROI, 2017 proved to be a more favorable year for all stocks except for TERP which had a -7.2% return. This return was calculcated by taking the ratio between net income and investment, where higher ROI demonstrates that the investments gains outrank the cost. Therefore, the same 12 stocks in 2018 proved to be less efficient and bring in decreasing returns in comparison to a year earlier. Interestingly, 2 stocks had high ROI in 2018 (ENPH and RUN), ENPH almost tripled its daily volume (from 221,772,100 to 607,473,500) and RUN doubled (from 267,681,300 to 502,757,100)-- with respective 81.9% and 84% returns. The changes in stock performance in 1 year time seems to highlight quite a volatile economic environment, potentially driving away future investors. Based off of this analysis, I would suggest for Steve to present the data on total daily volume in a bar chart for his parents and to advise them to be cautious with their interest in DQ. 
 
 ###### Analysis of execution time
 In comparing the execution time between the refactored script and the original script there is a large difference. For example, for the 2017 original analysis, it took 1.84 seconds.
 
  ![This is an image](https://github.com/leilacf/Stock-Analysis/blob/main/Original%20run%20time%202017.PNG)
  
  However, once done with the refactored script, it took 0.32 seconds.
  
  ![This is an image](https://github.com/leilacf/Stock-Analysis/blob/main/VBA_Challenge_2017.PNG)
  
  For the 2018 original analysis, it took 1.42 seconds.
  
  ![This is an image](https://github.com/leilacf/Stock-Analysis/blob/main/Original%20run%20time%202018.PNG)
  
  Lastly, when done with the refactored script, it took 0.49 seconds.
  
  ![This is an image](https://github.com/leilacf/Stock-Analysis/blob/main/VBA_Challenge_2018.PNG)
  
  
  # 3. Summary
  ## Advantages and Disadvantages
 ###### Advantages and disadvantages of refactoring code
 Advantages:
 - Refactoring can lead to a simplified way of re-utilizing code in a cleaner and more organized way
 - It can be less time consuming when delving into a new project
 - Can increase the transparency and scalability of a project
 - Can create increased general understanding when applied to various projects led by different individuals
 - In being able to restructure existing code, modernizing of systems and software can be facilitated

Disadvantages:
- Due to the nature of refactoring, if the code did not have comments or an organized system, it could lead to more confusion or loss for the user
- Increased chance of running into "errors", and therefore, making a project too time consuming
- Could reduce the maintainability of code and increase complexities 

###### Applying advantages and disadvantages to this analysis
In this analysis, there is quite an evident advantage shown with the execution time of the code. When using the refactored code, the analysis was done more rapidly using both the 2017 and 2018 data. Additionally, because we were able to use refactored portions of our code, the project became less time consuming. However, in terms of the disadvantages, I can imagine how it could have led to increased erros if the code had been copied wrong, or misused/misinterpreted--resulting in more challenges. In conclusion, utilizing refactored code in this project was beneficial.
