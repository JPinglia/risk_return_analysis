# Jas's Risk Adusted Return Analysis
The goal of this program is perform quantitative analysis for a Fin-Tech investing firm. We use look at four(4) new investment options and compaire them to the S&P 500 index fund. THe goal is to recommend a portfolio offering to clients, based on their investment style. 

Principals of:
 1) Daily returns
 2) Standard Deviation
 3) Sharpe Ratios
 4) Beta values
 5) Variance 
 6) Covariance 

are utilized to to help us determine an optimal protfolio offering.


## Technologies:

The program is written using Jupyter notebooks, for ease of code reading and code execution via code blocks. The program lays out a step-wise reporting and program execution. The code is run in a (apidev) environment with the use of the following libraries:
  1) Pandas
  2) Pathlib
  3) Matplotlib
  4) Numpy


## Installation Guide

Python 3.7.11 - base installation is required. PIP install jupyterlab


## Usage

Assumptions:

1) Risk Free Rate = 0 % in the Sharpe Ratio

The goal of the program is to analyize four funds vs the S&P index funds: Below is an example of the analysis conducted:

A) Checking individual fund daily returns perfromance vs. time.

![image_1_soros_fund_vs_time](https://user-images.githubusercontent.com/95830866/150721082-496c1532-ad41-4162-81f8-79ec7bf1a74b.PNG)

B) Next we compaire the fund performance to that of S&P 500 Index.

![image_2_fund_performance_vs_snp](https://user-images.githubusercontent.com/95830866/150721278-d4b447a9-c7f8-41d5-9d1b-fd891a6ce06c.PNG)

C) We need to check fund volitility by find ploting the mean and associated data point to assess fund volitility.

![image_3_fund_volitility](https://user-images.githubusercontent.com/95830866/150721350-34570579-a597-49ac-a662-6a752bafd6ab.PNG)

D) A moving average of 21-days is utalized to adjust the standard deviation. 

![image_4_sd_moving_average](https://user-images.githubusercontent.com/95830866/150721427-f1f92462-edfb-402b-8cb9-78fca2363191.PNG)

E) Sharpe Ratios of the funds is calculated and then compaired.

![image_5_sharpe_ratios](https://user-images.githubusercontent.com/95830866/150721467-c714cb89-96a0-4ede-8689-e97c59aec71c.PNG)


## Contributors
This program was developed with base code developed by the Rice-boot-camp. Code was created and added by JPinglia.


## License
License for this project and associated file is public.
