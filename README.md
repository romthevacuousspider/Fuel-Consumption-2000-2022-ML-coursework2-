The fuel consumption dataset is available on [Kaggle](https://www.kaggle.com/datasets/ahmettyilmazz/fuel-consumption?resource=download), the provider described: "Datasets provide model-specific fuel consumption ratings and estimated carbon dioxide emissions for new light-duty vehicles for retail sale in Canada. 
To help you compare vehicles from different model years, the fuel consumption ratings for 2000 to 2022 vehicles have been adjusted to reflect the improved testing that is more representative of everyday driving. Note that these are approximate values that were generated from the original ratings, not from vehicle testing."

The dataset was additionally added to my [github](https://github.com/romthevacuousspider/ML2-dataset) to avoid any possible further changes.


The Original data is extracted from [Open Canada Data](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64)

A description of the columns is provided below:

### Model

- 4WD/4X4: Four-wheel drive
- AWD: All-wheel drive
- CNG: Compressed natural gas
- FFV: Flexible-fuel vehicle
- NGV: Natural gas vehicle
- #: High output engine that provides more power than the standard engine of the same size

### Transmission

- A: Automatic
- AM: Automated manual
- AS: Automatic with select shift
- AV: Continuously variable
- M: Manual
- 3 - 10: Number of gears

### Fuel Type

- X: Regular gasoline
- Z: Premium gasoline
- D: Diesel
- E: Ethanol (E85)
- N: Natural Gas

### Fuel Consumption

City and highway fuel consumption ratings are shown in litres per 100 kilometres (L/100 km) - combined rating (55% city, 45% hwy) is shown in L/100 km and in miles per imperial gallon (mpg)
CO2 Emissions (g/km),Estimated tailpipe carbon dioxide emissions (in grams per kilometre) are based on fuel type and the combined fuel consumption rating.

Based on this [article](https://www.ageco.co.uk/useful-articles/car/what-are-the-co2-emissions-of-my-car/) we can classify the cars by their emission:

- 150g/km emission is considered low
- 160 to 255g/km emission is considered medium
- Above 255g/km emission is considered high
