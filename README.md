# Bankruptcy-Prevention
To predict if a company will file for bankruptcy or not using the given data

# Problem Statement
   To predict if a company will file for bankruptcy or not using the given data

# Business understanding

Bankruptcy prediction, also named as corporate bankruptcy prediction or corporate failure prediction, has long been a significant topic in the field of accounting and finance, since the health of a firm is highly important to its creditors, investors, shareholders, partners, even its buyers and suppliers. 

Bankruptcy is a state where a company is not able to run its business or continue its operation in the future because of its financial condition or debts. Any firm or investor needs to know the state of bankruptcy before they start investing in the company. Having a standardized approach looks like a generous idea in predicting any state but is very unlikely that the method will give satisfying results because of the real-world situations established.

Researchers and practitioners have been dedicated to developing methods and techniques to predict the bankruptcy of firms more quickly and more accurately.

# Objective of the analysis

The goal of this project is to build a model that can predict Bankruptcy. The challenge behind Bankruptcy prediction in machine learning is that Bankruptcy samples are far less common as compared to Non-Bankruptcy.

Bankruptcy prediction is a challenging problem, given the variety of Bankruptcy patterns and relatively small ratio of known Bankruptcy in typical samples. While building prediction models, the savings from loss prevention needs to be balanced with the cost of false alerts. Machine learning techniques allow for improving predictive accuracy, enabling loss control units to achieve higher coverage with low false positive rates. 

Using the given data, different types of  machine learning models are build by varying different parameters in each type of model. The accuracy, recall and precision are checked for each model. The model which gives the best results is selected as our final model which clearly classifies whether a company goes Bankruptcy or not.

# About The Dataset

## Input variables:

The data file contains 7 features about 250 companies
The data set includes the following variables:

1.industrial_risk      : 0=low risk, 0.5=medium risk, 1=high risk.

2.management_risk       : 0=low risk, 0.5=medium risk, 1=high risk.

3.financial flexibility : 0=low flexibility, 0.5=medium flexibility, 1=high flexibility. 

4.credibility           : 0=low credibility, 0.5=medium credibility, 1=high credibility.

5.competitiveness       : 0=low competitiveness, 0.5=medium competitiveness, 1=high competitiveness.

6.operating_risk        :  0=low risk, 0.5=medium risk, 1=high risk.

7.class                 :  bankruptcy, non-bankruptcy (target variable).


Following are the details of the qualitative risk factors which mentions their risk components:

+ Industry risk : Government policies and International agreements, Cyclicality, Degree of competition, The price and stability of market supply, The size and growth of market demand, The sensitivity to changes in macroeconomic factors, Domestic and international competitive power, Product Life Cycle.

+ Management risk : Ability and competence of management, Stability of management, The relationship between management/ owner, Human resources management, Growth process/business performance, Short and long term business planning, achievement and feasibility.

+ Financial Flexibility : Direct financing, Indirect financing, Other financing

+ Credibility : Credit history,reliability of information, The relationship with financial institutes.

+ Competitiveness : Market position, The level of core capacities, Differentiated strategy,

+ Operating Risk (OP): The stability and diversity of procurement, The stability of transaction, The efficiency of production, The prospects for demand for product and service, Sales diversification, Sales price and settlement condition, Collection of A/R, Effectiveness of sale network.
