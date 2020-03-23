# covid19
Data science experiments with Johns Hopkins COVID-19 dataset

Jay Urbain, PhD

COVID-19 Logistic Model

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

Last update: 3/23/2020

The logistic model has been widely used to describe population growth such as the spread of a virus through the population. 

$$
f(x,a,b,c) = \dfrac{c}{1 + e^{-(x-b)/a}}
$$

- $x$ = time (days)
- $a$ = infection speed
- $b$ = inflection point (days), day with max rate of new infections 
- $c$ = total number of recorded infected people at the end

The number of infected people eventually gets close $c$ where the infection has ended. 

The inflection point $b$, is the point at which the rate of infection starts to decrease (max first derivative).

A plot of a generic logistic function is shown below.

<img src="logistic_function.png" width="600px">

<img src="Logistic Model South Korea.png" width="400px">

<img src="Scaled S. Korea Logistic Model, US Data.png" width="400px">

<img src="China Hubei Logistic Model.png" width="400px">

<img src="Scaled China Hubei Logistic Model, US Data.png" width="400px">

<img src="Italy Logistic Model.png" width="400px">

<img src="Scaled Italy Logistic Model, US Data.png" width="400px">

<img src="Projections for US Cases following the South Korea, Hubei Province (China), and Italy Trajectories.png" width="600px">

<img src="US Covid cases numbers.png" width="400px">

<img src="US Covid dates.png" width="400px">





