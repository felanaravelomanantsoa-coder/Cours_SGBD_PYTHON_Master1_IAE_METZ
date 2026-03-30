# Cours_SGBD_PYTHON_Master1_IAE_METZ
# Ceci est le repository pour les étudiants IAE Metz 2027

# Project : Historical simulation of Value at Risk (VaR) for the DAX 40 index 

Problem Statement : Estimate the DAX 40's historical VaR to quatify its downside risk over a chosen horizon of 5 years and a confidence level of 95%

Objectives : 
-> Download daily price data of the DAX 40 from API Yahoo Finance (Application Programming Interface) via the yfinance library

-> Compute daily returns based on closing prices (logarithmic returns) 

-> Clean and structure the dataset by handling missing values and filtering the 5-year study period 

-> Store the transformed data in a SQLite database to ensure clean, reproductible, and well-structured data management 

-> Compute the historical Value at Risk (VaR) at the 95% confidence level

-> Visualize the empirical distribution of returns and hilight the VaR threshold on the plots 

-> Present the final results in a Streamlit dashboard

get git clone https://github.com/felanaravelomanantsoa-coder/Cours_SGBD_PYTHON_Master1_IAE_METZ/edit/main/README.md

