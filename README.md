# mebfaber_gtaa_model_backtest

## Description

Meb Faber's "A Quantitative Approach to Tactical Asset Allocation" outlines a systematic, rules-based strategy that uses historical data and moving averages/momentum to time the market. By switching between asset classes based on these trends, the approach aims to maximize returns and minimize risk, providing a clear, quantitative framework for investment decisions.

However, the results produced by the paper seem too good to be true, consistently beating the market in every test. Therefore, this project aims to first replicate exactly Meb Faber's model and results as shown in his paper, then conduct necessary sensitivity analysis determine whether this strategy is applicable in real life investment practices. 

## Usage

There are two main source code files, coded on python 3 and ran on Jupyter. The first one: "Replication of Meb Faber's Momentum Based SMA Timing Strategy" replicates the contents of the paper and performs the necessary sensitivity analysis. The second one: "Dynamic Weighting Allocation Extension" is an extension based on pure interest. It explores a new and improved version of the model by adding dynamic weighting based on momentum every time the model is updated. 

The data used are included in seperate excel files and was collected from various sources including Bloomberg Terminal.

## Installation instructions:

1. Download all the files
2. Ensure pandas, numpy, and matplotlib are downloaded in the environment
3. Run the main source codes on Jupyter Lab or Notebook
4. Restart and run all kernels 

## Extensions

1. Consider external costs such as transaction costs and taxes
2. Consider a portfolio with other assets besides the 5 used in Meb Faber's GTAA model
3. 
