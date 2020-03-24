# covid19
Data science experiments with Johns Hopkins COVID-19 dataset

Jay Urbain, PhD

COVID-19 Logistic Model

Last update: 3/23/2020

The logistic function has been widely used to describe population growth such as the spread of a virus through the population.

The spread of a pathogen can start out slowly, but as larger numbers of the susceptible population become infected, the number of infected experiences exponential growth. Eventually this growth levels off as the size of the susceptible population decreases and the populations of the infected and recovered increase.

Data from the reference regions (Italy, South Korea, and Hubei province China) are each fitted with a logistic function beginning on the day of the 100th confirmed case in that country.  

The models for the three countries are then scaled to the U.S. population and aligned along the time-axis to best fit the US data for total confirmed cases.  

Graphing these projections together demonstrates how the U.S. compares to benchmark regions, to help give more clarity in what the U.S. path going forward might look like.

<img src="Projections for US Cases following the South Korea, Hubei Province (China), and Italy Trajectories.png" width="800px">

<img src="US Logistic Model, US Data.png" width="800px">

#### US Model Stats
> a = 1.992449043874816 +/- 0.10901005109056824
> 
> b = 58.59553015123753 +/- 0.26374194255192546
> 
> c = 45683.220504305216 +/- 2514.2998715231024
> 
> errors [0.10901005109056824, 0.26374194255192546, 2514.2998715231024]
> 
> Expected number of infected people at infection end: 45683.22 +/- 2514.3
> 
> Infection peak in days from start: 58.6 +/- 0.26
> 
> us_inflection_date 2020-03-20T00:00:00.000000000
> 
> us_inflection_date_string 2020-03-20
> 
> days end 82
> 
> infection_end_date_string 2020-04-13

#### S. Korea, China Hubei, and Italy Models Scaled for US Population

> US Inflection Date South Korea Model 2020-03-23
> 
> US Spread Tail Off Date South Korea Model 2020-05-23
> 
> US Inflection Date China Hubei Model 2020-04-01
> 
> US Spread Tail Off Date China Hubei Model 2020-06-10
> 
> US Inflection Date Italy Model 2020-04-03
> 
> US Inflection Date Italy Model 2020-06-14

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





