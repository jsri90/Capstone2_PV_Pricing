# Solar Energy - a good long term bet?

Photovoltaic installations are a increasing in number and with a growing concern about global warming, the technology needs to be adopted more. In order for an increased adoption, this has to be a financialy viable option for the end consumer. In order to achive that target, there needs to be improvement in the Photo Voltaic (PV) technology. Additionally, PV installers need to be able to provide a cost effective solution that offers a benefit to the end user in the long run. In order for PV installers to develop such a solution, they need to understand the impact of the different factors affecting the price of a PV installation system.

The aim of this project is to provide a data driven analsysis of the various cost factors that they can then use to estimate the costs of a PV system.

## Data Source
The data and regression analysis for this project has been referenced from the Tracking the Sun Report developed by Lawrence Berkley Laboratory
- https://emp.lbl.gov/tracking-the-sun

## Objective
The objective here is to be able to predict the price of a solar installtion in terms of $/ kW. Please note this cost excludes any incentives, taxes or labor related costs. The cost calculated is solely based on technological characteristics such as System size, Module efficiency, Installer name / experience, location. 

## Analysis
The analysis here is done using multiple models - 

 - Dummy Regressor
 - Linear Regressor
 - Random Forest Regressor

## Results
We see that the Random Forest Regressor has the best performance and given the information such as the features in this dataset we are able to predict the price of a PV installation with an average margin of error of $1.7. 
