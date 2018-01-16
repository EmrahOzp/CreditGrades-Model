# CreditGrades-Model
Estimating prob (survival) and Prob (default) using balance sheet and market information
Creditgrades, is an alternative structural modelling approach. in this model, default occurs if the asset value of the firm drops below a random barrier. the randomness of the barrier is the main difference when compared to the other models. it captures the fact that we usually do not know the level of firm's liabilities untill the firm defaults. 

CG model, assumes that default can occur at any time , whereas default in the classical Merton model occurs only at maturity.

The parameters;

The number of shares used for computing per-share figure is the number of common shares plus the number of preffered shares. 
the number of common shares can be determined by dividing the company's MC by current stock price. the number of preffered shares is calculated by dividing the book value of prefffered shares by the price of common stock from the reporting date of book value. 

the debt per share meaure is calculated by dividing liabilities by the number of shares. 
