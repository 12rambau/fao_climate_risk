# fao_climate_risk
create maps for climate risk, accessibility to cities, and declining population

## Data
- future climate risk from J-F Bastin & Al.
- Accecibility to cities 2015
- 2020 Gridded Population of the World (GPW v4.11)
- 2010 GPW

create maps for the study of croplands in LMIC

## output 
- `future_risk.tif` : future climate risk from J-F Bastin & Al. 
- `accecibility_masked.tif` : Accecibility map aligned on the future risk raster
- `population_decline_masked.tif` : declin of the population between 2020 and 2010 aligned on the future risk raster


## usage 

on an instance >= `m4`, pull the repository in your sepal environment:
```
git clone https://github.com/12rambau/fao_climate_risk.git
```
