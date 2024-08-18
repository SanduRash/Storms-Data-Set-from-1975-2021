# The Dataset of Storms from 1975-2021

I conducted an exploratory data analysis to identify patterns and relationships within the dataset.

This dataset is the NOAA Atlantic hurricane database best track data.
The data includes the positions and attributes of storms from 1975-2021. Storms from 1979 onward are measured every six hours during the lifetime of the storm. This have 19066 observations and 13 variables.

-   name: Storm Name

-   year,month,day: Date of report

-   hour: Hour of report (in UTC)

-   lat,long: Location of storm center

-   status: Storm classification (Tropical Depression, Tropical Storm, or Hurricane)

-   category: Saffir-Simpson hurricane category calculated from wind speed.

-- NA: Not a hurricane

-- 1: 64+ knots

-- 2: 83+ knots

-- 3: 96+ knots

-- 4: 113+ knots

-- 5: 137+ knots

-   wind: storm's maximum sustained wind speed (in knots)

-   pressure: Air pressure at the storm's center (in millibars)

-   tropicalstorm_force_diameter: Diameter (in nautical miles) of the area experiencing tropical storm strength winds (34 knots or above). Only available starting in 2004.

-   hurricane_force_diameter: Diameter (in nautical miles) of the area experiencing hurricane strength winds (64 knots or above). Only available starting in 2004.

<br/>
As a result, I could visualize frequency trends over time and by category, identify peak activity months, investigate the relationship between wind speed, air pressure and 
their correlation using a linear regression model.

