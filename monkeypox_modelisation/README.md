# MONKEYPOX MODELING

#### Aurélien Vannieuwenhuyze - 2022/08/03 - Mathematics  
##### https://aurelienvannieuwenhuyze.com | https://qstom-it.com  
<img src="https://www.gnu.org/graphics/gplv3-127x51.png"/>

<hr>

## Abstract

Monkeypox is a disease that has been on the rise again across several continents in recent months.(Aout 2022)

This notebook allows you to :
- Visualize the development of the actual disease (2022)  
- Modeling an epidemic with SIR model
- Use the Euler method to create a SIR model
- Use SciPy to create a SIR model
- Understand an SVEIR Model
- Visualize the impact of the use of a vaccine on this disease with the help of mathematical modeling
- Make a tool for epidemic interactive modeling

The modeling work of the Monkeypox disease is based on the scientific publication of
> Usman, S. and
Adamu, I.I. (2017) Modeling the Transmission Dynamics of the Monkeypox Virus
Infection with Treatment and Vaccination
Interventions. Journal of Applied Mathematics and Physics, 5, 2335-2353.
https://doi.org/10.4236/jamp.2017.512191  
https://www.scirp.org/pdf/JAMP_2017121414351920.pdf


**You must read this scientific publication before execute each parts of codes**

<br>

Attention:
This note book was created for educational purposes.
The objectives are as follows:
- Understanding, analysis and implementation of a scientific publication

**The information in this notebook cannot be used for real-life simulations.**

# Content
## Abstract
## Datas and python libraries
### Libraries
### Datas
## Datas visualization (geopandas and folium)
### Loading datas
### Adding GPS Coordinates
### France Analysis
### Geopandas and Folium visualization
#### Group by location, aggregation by total_cases
#### Visualization
## Modeling an epidemic
### SIR model
#### Understanding the SIR model
##### Using number of individuals in each population classes instead of percentages
#### Euler's method for solving the SIR model
#### Using odeint method (Ordinary Differential Equation) from Scipy package
## Modeling the transmission dynamic of the Monkeypox with treatment and vaccination interventions
### Description of the SVEIR compartmental model
### Name of model parameters
#### Non-human population (monkey)
#### Human population
## Differentials equations and modeling
### Non human population
#### Parameters
#### Susceptible non-human subpopulation differential equation
#### Exposed non-human subpopulation differential equation
#### Infected non-human subpopulation differential equation
#### Recovered non-human subpopulation differential equation
#### SEIR Modeling for non-human population
#### R0 (Reproduction rate) for non-human
### Human population with vaccine treatment
#### Parameters
#### Susceptible human subpopulation differential equation
#### Vaccined human subpopulation differential equation
#### Exposed human subpopulation differential equation
#### Infected human subpopulation differential equation
#### Recovered humain subpopulation differential equation
#### SVEIR Modeling (with vaccine) for human population
#### R0 for human population
## Interactive modeling
## Sources
