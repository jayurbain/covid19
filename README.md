# covid19
Data science experiments with Johns Hopkins COVID-19 dataset

COVID-19 Logistic Model

Last update: 3/25/2020

The logistic function has been widely used to describe population growth such as the spread of a virus through the population.

The spread of a pathogen can start out slowly, but as larger numbers of the susceptible population become infected, the number of infected experiences exponential growth. Eventually this growth levels off as the size of the susceptible population decreases and the populations of the infected and recovered increase.

Data from the reference regions (Italy, South Korea, and Hubei province China) are each fitted with a logistic function beginning on the day of the 100th confirmed case in that country.  

The models for the three countries are then scaled to the U.S. population and aligned along the time-axis to best fit the US data for total confirmed cases.  

Graphing these projections together demonstrates how the U.S. compares to benchmark regions, to help give more clarity in what the U.S. path going forward might look like.

<img src="Projections for US Cases following the South Korea, Hubei Province (China), and Italy Trajectories.png" width="800px">

<img src="US Logistic Model, US Data.png" width="800px">

#### US Model Stats
> a = 2.628809337950645 +/- 0.054813613261587894
> 
> 
> b = 62.3277521558533 +/- 0.26525421817170247
> 
> c = 115146.14962413454 +/- 6373.962413292967
> 
> errors [0.054813613261587894, 0.26525421817170247, 6373.962413292967]
> 
> Expected number of infected people at infection end: 115146.15 +/- 6373.
> 
> Infection peak in days from start: 62.33 +/- 0.27
> 
> us_inflection_date 2020-03-24T00:00:00.000000000
> 
> us_inflection_date_string 2020-03-24
> 
> days end 97
> 
> infection_end_date_string 2020-05-24

#### S. Korea, China Hubei, and Italy Models Scaled for US Population

<img src="logistic_modeling.png" width="800px">

<img src="logistic_function.png" width="800px">

<img src="Logistic Model South Korea.png" width="600px">

<img src="Scaled S. Korea Logistic Model, US Data.png" width="600px">

<img src="China Hubei Logistic Model.png" width="600px">

<img src="Scaled China Hubei Logistic Model, US Data.png" width="600px">

<img src="Italy Logistic Model.png" width="600px">

<img src="Scaled Italy Logistic Model, US Data.png" width="600px">

References:

Interview Ari Libsker, Corona Is Slowing Down, Humanity Will Survive, Says Biophysicist Michael Levitt, 3/13/20.
https://www.calcalistech.com/ctech/articles/0,7340,L-3800632,00.html

Chowell, G., Sattenspiel, L., Bansal, S., & Viboud, C. (2016). Mathematical models to characterize early epidemic growth: A review. Physics of life reviews, 18, 66–97. https://doi.org/10.1016/j.plrev.2016.07.005

2019 Novel Coronavirus COVID-19 (2019-nCoV) Data Repository by Johns Hopkins CSSE
https://github.com/CSSEGISandData/COVID-19

Exponential growth and epidemics, CDC
https://www.youtube.com/watch?v=Kas0tIxDvrg

Estimating actual COVID 19 cases (novel corona virus infections) in an area based on deaths, CDC
https://www.youtube.com/watch?v=mCa0JXEwDEk

Mathematics of the Corona outbreak – with professor Tom Britton
https://www.youtube.com/watch?v=gSqIwXl6IjQ





