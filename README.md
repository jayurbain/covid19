## COVID-19 Logistic Model

Data science experiments with Johns Hopkins COVID-19 dataset

Jay Urbain, PhD

Last update: 3/27/2020

<img src="logistic_modeling.png" width="800px">

<img src="logistic_function.png" width="800px">

The spread of a pathogen can start out slowly, but as larger numbers of the susceptible population become infected, the number of infected experiences exponential growth. Eventually this growth levels off as the size of the susceptible population decreases and the populations of the infected and recovered increase.

#### US Model Stats - includes data up to an including 2/26/2020

<img src="US Logistic Model, US Data.png" width="800px">

> a = 2.9807672688165514 +/- 0.062400293161278486
> 
> b = 64.47652180494909 +/- 0.3110206724571872
> 
> c = 179433.84849847297 +/- 10388.850161718614
> 
> errors [0.062400293161278486, 0.3110206724571872, 10388.850161718614]
> 
> Expected number of infected people at infection end: 179433.85 +/- 10388.85
> 
> Infection peak in days from start: 64.48 +/- 0.31
> 
> us_inflection_date 2020-03-26T00:00:00.000000000
> 
> us_inflection_date_string 2020-03-26
> 
> days end 101
> 
> infection_end_date_string 2020-05-20


Data from the reference regions (Italy, South Korea, and Hubei province China) are each fitted with a logistic function beginning on the day of the 100th confirmed case in that country.  

The models for the three countries are then scaled to the U.S. population and aligned along the time-axis to best fit the US data for total confirmed cases.  

Graphing these projections together demonstrates how the U.S. compares to benchmark regions, to help give more clarity in what the U.S. path going forward might look like.

#### Model Trajectories - includes data up to an including 2/26/2020

<img src="Projections for US Cases following the South Korea, Hubei Province (China), and Italy Trajectories.png" width="800px">

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





