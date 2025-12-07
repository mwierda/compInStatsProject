# compInStatsProject
Computing in Statistics computing project code repository

Decent amount of comments in the code covering what happened, but we tried to follow the paper's methodology as closely as possible so you should be able to largely just talk about what they did and be fine.

In our conclusion we weren't able to see the same amount of difference in variance as they did, though we did still see a reduction in it by including temperature data in our model. This is possibly due to some remaining auto-correlation in the data that the ARIMA model wasn't able to get rid of - possibly due to replacing weekend values with averages of the following week, maybe due to this being 30 years later and us having better models, we're not sure.

Additionally they took data from north-east USA - electricity load and temperature data - whereas ours was all from Spain, with the temperature data from Madrid specifically. I don't expect this to have much of an impact, but maybe we have better data collection methods now or load generation is more consistent/smooth which causes less variance.

The monte carlo part is kinda hard to understand code wise, so should be able to just talk about monte carlo in general and run through the paper's procedure. We followed it as best we could so should be sufficient for the presentation.

Our conclusion essentially matches theirs, we just didn't find as much variance by including temperature.
