# BA_Bootcamp_3_Google_Causal_Impact_Challenge


# Google Causal Impact Challenge: Volkswagen CO2 Scandal

# Overview

    This repository contains a Google Colaboratory notebook that applies Google 
    Causal Impact to analyze the Volkswagen CO2 scandal and its effect on 
    Volkswagen's stock price. The challenge is to measure the financial impact 
    of the scandal by using econometric techniques and causal inference methods.

# Challenge Description

    In September 2015, it was revealed that Volkswagen had misled customers by 
    underreporting vehicle CO2 emissions. This scandal significantly affected 
    Volkswagen’s stock price, but the question is: how much did it actually 
    impact the company’s market value?
    
    The objective is to use Google Causal Impact to quantify the stock price 
    drop while accounting for external market influences.
    

# Topics Covered

1. Why Econometrics and Causal Inference?

        * Importance of causality in financial market analysis.
        
        * Differentiating market trends from company-specific shocks.

3. Google Causal Impact Game Plan

        *  Step-by-step guide on how to implement Causal Impact.
        
        *  Selecting an appropriate control group to isolate the scandal's effect.

3. Volkswagen CO2 Scandal Case Study

        * Event Date: September 2015.
        
        * Research Question: How much market value did Volkswagen lose due to the scandal?

4. Time Series Data

        * Gathering historical Volkswagen stock data.
        
        * Retrieving stock prices for potential control groups.

5. Defining the Control Group

        * Key Decision: Avoid using other automotive companies as they might have
          been affected by the scandal.
        
        * Selecting independent but comparable stocks that reflect normal market movements.

7. Correlation Matrix and Stationarity Check

        * Performing correlation analysis on potential control variables during the
         pre-scandal period.
        
        * Ensuring stationarity to create a valid control group.

9. Applying Google Causal Impact

        * Setting up pre-treatment and post-treatment periods.
        
        * Running the Causal Impact model to measure Volkswagen’s stock drop.
        
        * Analyzing both absolute and cumulative impact metrics.

10. Interpretation of Results

        * Evaluating the observed vs counterfactual price evolution.
        
        * Identifying statistical significance of the stock drop.
        
        * Discussing the broader financial implications of the scandal.


# Implementation Details

        *  Financial Data Source: Yahoo Finance (yfinance library).
        
        *  Statistical Methods: Augmented Dickey-Fuller Test, Correlation Matrix.
        
        *  Libraries Used:

                --> yfinance (for retrieving stock data)
                
                --> causalimpact (Google Causal Impact analysis)
                
                --> pandas, seaborn, matplotlib (for data processing & visualization)
