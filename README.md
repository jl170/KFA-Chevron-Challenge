# KFA-Chevron-Challenge
This is team KFA's entry for the 2023 Rice Datathon

As investment in renewable energy increases in America, 
Chevron wishes to select the most promising states to invest in.
To do this, Chevron starts with the assumption that the state with 
the largest total investment received will be the most promising.

Therefore, we wish to predict the Renewable Energy Investments ($) 
of each US state for 2020, using data from 2019 or prior.
The data that we are using are 30 different natural resource-related values,
which are attributed to each state and year.
We must train a regression model with this data to predict the statewide investments.

In the Presentation_Notebook we have most of the code we used to reach the very unfortunate conclusion that the very naive benchmark of taking themean of each states' Assistances from the past five years performed the best.

In the GPR_Analysis we have results from attempting to use GPR.