# ubiquant market prediction

PDM new ubiquant_market_prediction

## Result
* Silver Medal
* 142 of 2,893
* [leader board](https://www.kaggle.com/competitions/ubiquant-market-prediction/leaderboard)

## Description

Regardless of your investment strategy, fluctuations are expected in the 
financial market. Despite this variance, professional investors try to estimate 
their overall returns. Risks and returns differ based on investment types and 
other factors, which impact stability and volatility. To attempt to predict 
returns, there are many computer-based algorithms and models for financial 
market trading. Yet, with new techniques and approaches, data science could 
improve quantitative researchers' ability to forecast an investment's return.

![1.jpg](assets%2F1.jpg)

Ubiquant Investment (Beijing) Co., Ltd is a leading domestic quantitative hedge 
fund based in China. Established in 2012, they rely on international talents in 
math and computer science along with cutting-edge technology to drive 
quantitative financial market investment. Overall, Ubiquant is committed to 
creating long-term stable returns for investors.

In this competition, you’ll build a model that forecasts an investment's return 
rate. Train and test your algorithm on historical prices. Top entries will 
solve this real-world data science problem with as much accuracy as possible.

If successful, you could improve the ability of quantitative researchers to 
forecast returns. This will enable investors at any scale to make better 
decisions. You may even discover you have a knack for financial datasets, 
opening up a world of new opportunities in many industries.

See more information about Ubiquant: [Ubiquant Video](https://www.youtube.com/watch?v=PCzi76d-W6o)

## Evaluation
Submissions are evaluated on the mean of the Pearson correlation coefficient 
for each time ID.

You must submit to this competition using the provided python time-series API, 
which ensures that models do not peek forward in time. To use the API, follow 
this template in Kaggle Notebooks:

```python
import ubiquant
env = ubiquant.make_env()   # initialize the environment
iter_test = env.iter_test()    # an iterator which loops over the test set and sample submission
for (test_df, sample_prediction_df) in iter_test:
    sample_prediction_df['target'] = 0  # make your predictions here
    env.predict(sample_prediction_df)   # register your predictions
```

You will get an error if you submission includes nulls or infinities and 
submissions that only include one prediction value will receive a score of -1.

## Timeline
EDIT: The final submission deadline has been extended 48 hours due to reports 
of an inability to submit

This is a forecasting competition with an active training phase and a second 
period where models will be run against real market data.

Training Timeline
* January 18, 2022 - Start Date.
* April 11, 2022 - Entry Deadline. You must accept the competition rules before this date in order to compete.
* April 11, 2022 - Team Merger Deadline. This is the last day participants may join or merge teams.
* April 20, 2022 - Final Submission Deadline.

All deadlines are at 11:59 PM UTC on the corresponding day unless otherwise 
noted. The competition organizers reserve the right to update the contest 
timeline if they deem it necessary.

### Forecasting Timeline:
Starting after the final submission deadline there will be periodic updates to 
the leaderboard to reflect data updates that will be run against selected 
notebooks. Updates will take place roughly every two weeks.

* July 18th, 2022 - Competition End Date

## Prizes
* 1st Place - $40,000
* 2nd Place - $20,000
* 3rd Place - $10,000
* 4th Place - $5,000
* 5th Place - $5,000
* 6th Place - $5,000
* 7th Place - $5,000
* 8th Place - $3,500
* 9th Place - $3,500
* 10th Place - $3,000

## Code Requirements
This is a Code Competition. Submissions to this competition must be made 
through Notebooks. In order for the "Submit" button to be active after a 
commit, the following conditions must be met:

* CPU Notebook <= 9 hours run-time
* GPU Notebook <= 9 hours run-time
* Internet access disabled
* Freely & publicly available external data is allowed, including pre-trained models

Please see the Code Competition FAQ for more information on how to submit. And 
review the code debugging doc if you are encountering submission errors.

## Ubiquant Contact Information
During the competition, participants are encouraged to use the Discussion 
Forums to discuss techniques and ask questions. Should you have other questions 
for the competition sponsor, or be interested in employment with Ubiquant, see 
the links below.

For more information, check out the following:
* [Official website of Ubiquant](https://www.ubiquant.com/website/home)
* [Official website for recruitment](https://app.mokahr.com/apply/ubiquantrecruit/37030#/)
* [Competition email address](hackathon@ubiquant.com)
* [Recruitment email address](recruiter@ubiquant.com)

--------------------------------------------

# EDA

# Fast data loading

# Feature Engineering

# LGBM approach

# DNN approach

