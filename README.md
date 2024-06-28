Task
The challenge is set in the context of performance marketing and we want you to apply a bayesian mixed-media model (MMM) on our test dataset an interpret the insights from the model. Build the MMM with the latest PyMC package (https://www.pymc.io/).

Context
We have a company X which runs an online shop. X advertises on seven different paid channels and has weekly costs in them. Marketing actions have usually not an immediate effect, ads and campaigns in one week influence usually sales in the coming weeks. Hence, the company is of course super interesting to understand how effective different channels are. In terms of channels think of TV, radio, billboards, but also online advertisement such as Google Ads, Facebook Ads, etc. So different channel can be expected to target different audiences at different times, and hence will have very different effects on future sales.

This is of course the perfect setting for an ambitious Data Scientist. ;-) Modelling the uncertainty and the delayed effects is of course key. We are working heavily with Bayesian models and would like here to test your understanding and approaches in this setting.


You will need to model the spend carry over effect (adstock).
No need (for now) to overcomplicate the adstock shape effects with saturation or diminishing returns.
Seasonality & trend might be interesting to be included in your model.
Dataset MMM_test_data.csv
start_of_week: first day of the week
revenue: revenue generated in this week from sales
spend_channel_1..7: marketing cost spend in this week in channel 1..7
Questions
How do you model spend carry over?
Explain your choice of prior inputs to the model?
How are your model results based on prior sampling vs. posterior sampling?
How good is your model performing? How you do measure it?
What are your main insights in terms of channel performance/ effects?
(Bonus) Can you derive ROI (return on investment) estimates per channel? What is the best channel in terms of ROI?
