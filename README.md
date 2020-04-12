## COVID-19 Logistic Model

Data science experiments with Johns Hopkins COVID-19 dataset

Jay Urbain, PhD

Last update: 4/12/2020

<img src="logistic_modeling.png" width="800px">

<img src="logistic_function.png" width="800px">

The spread of a pathogen can start out slowly, but as larger numbers of the susceptible population become infected, the number of infected experiences exponential growth. Eventually this growth levels off as the size of the susceptible population decreases and the populations of the infected and recovered increase.

Data from the reference regions (Italy, South Korea, and Hubei province China) are each fitted with a logistic function beginning on the day of the 100th confirmed case in that country.  

The models for the three countries are then scaled to the U.S. population and aligned along the time-axis to best fit the US data for total confirmed cases.  

Graphing these projections together demonstrates how the U.S. compares to benchmark regions, to help give more clarity in what the U.S. path going forward might look like.

#### Model Trajectories - includes data up to an including 4/11/2020

<img src="Projections for US Cases following the South Korea, Hubei Province (China), and Italy Trajectories.png" width="800px">

#### US Model Stats - includes data up to an including 4/11/2020

It is not clear that the US has passed an inflection point, so expect the model to be highly variable.

<img src="US Logistic Model, US Data composite.png" width="800px">

> a = 4.898674995522961 +/- 0.07189501827354033
> 
> b = 73.63661646344273 +/- 0.17644070987667304
> 
> c = 656134.2531105597 +/- 9902.673786111522
> 
> errors [0.07189501827354033, 0.17644070987667304, 9902.673786111522]
> 
> Expected number of infected people at infection end: 656134.25 +/- 0.18
> 
> Infection peak in days from start: 73.64 +/- 0.18
> 
> us_inflection_date 2020-04-04T00:00:00.000000000
> 
> us_inflection_date_string 2020-04-04
> 
> days end 145
> 
> infection_end_date_string 2020-06-14

#### Daily Percent Change in US Cases

On the positive side, the percent change in US cases has been steadily 
decreasing. When this value goes below zero, the number of new cases 
reported each day will start to decrease.

<img src='Percent Change US Cases.png' width="600px">

#### S. Korea Piecewise Logistic-Quadratic Model, South Korea Data

<img src="Piecewise Logistic-Quadratic Model South Korea.png" width="600px">

#### S. Korea, China Hubei, and Italy Models Scaled for US Population

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





