---
title       : The Greenhouse Effect
subtitle    : with slidify
author      : K V Satyanarayana
job         : DGM
framework   : io2012       # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- 
### Why greenhouse? 
 The term greenhouse effect comes from the idea that the atmosphere traps heat in the troposphere like the glass walls of a greenhouse do
Without these gases the earth would be frozen like Mars
### What are greenhouse gasses?
Small amounts of specific gasses act as insulators in the atmosphere
These are known as greenhouse gasses and include the following:

1. Carbon dioxide (CO2)
2. Water vapor (H2O)
3. Methane (CH4)
4. Nitrous Oxide (N2O)

---  

### What do greenhouse gasses do?

1. Sunlight heats up the earth's surface .
2. The earth's surface reflects the heat.
3. The greenhouse gasses absorb the heat and warm the troposphere.
4. These greenhouse gasses occur naturally in the atmosphere.
5. Without the greenhouse gasses, earth would be cold and lifeless.

### Natural Greenhouse Gasses

Volcanoes are one source of natural greenhouse gasses
Swedish chemist Svante Arrhenius first recognized the natural warming effect of gasses in the troposphere. 

--- 
### Historical Record
- Bubbles in the ancient ice will contain samples of the ancient atmosphere.
- By analyzing these ancient air samples scientists can discover the greenhouse gas levels in the atmosphere thousands of years ago.
- Records exist to describe the atmosphere for the past 160,000 years, Since 1958 records of atmospheric CO2 levels have been collected.
- Carbon dioxide levels will fluctuate during the year according to the seasons - lower in the summer and higher in the winter.
- Even with these fluctuations during the year the average CO2 levels are rising.
- Sometimes plants will be buried under silt and compressed over millions of years,this organic matter is turned into coal, oil, and natural gas.We burn this for energy and release carbon dioxide into the atmosphere.
- As a result most scientists now believe that the extra greenhouse gasses are warming the atmosphere.
- In addition to carbon dioxide, we are also releasing many other additional greenhouse gasses which are warming the atmosphere too.

--- 
### Effects of warming

- As the earth warms up, so do the oceans.  
- Warmer oceans may make hurricanes and typhoons more common 
- They may also lead to changes in the pattern of ocean currents 
- Droughts could become more frequent and impact agriculture
- As the Earth warms, the ice caps and glaciers will start to melt.

 This could lead to rising sea levels that have several consequences:
  1. Coastal wetlands and low-lying areas are flooded.
  2. People who live near the coast loose their homes and livelihood.
  3. Salt water enters coastal aquifers. 


---
### CALCULATION METHOD FOR CARBON DI-OXIDE EMMISIONS
To calculate the CO2 emission from a fuel the carbon content of the fuel must be multiplied with the ratio of molecular weight CO2 (44) to the molecular weight Carbon 12 -> 44 / 12 = 3.7

Carbon Dioxide emission can be calculated as

qCO2 = cf / hf  CCO2/Cm         (1)

where

  - qCO2 = specific CO2 emission (CO2/kWh)
  - cf = specific carbon content in the fuel (kgC/kgfuel)
  - hf = specific energy content (kWh/kgfuel)
  - Cm = specific mass Carbon (kg/mol Carbon)
  - CCO2 = specific  mass Carbon Dioxide (kg/mol CO2)

---
### Normal carbon dioxide emmision with common fuels
Emission of Carbon Dioxide - CO2 - when combustion some common fuels are indicated in the table below.

Note! Heat loss - 55-75% - in power generation is not included in the numbers.   

Fuel  Specific Carbon Content

```
##        Item FuelSpecificCarbonContent SpecificEnergyContent
## 1     Coal                       0.75                   0.9
## 2  Gasoline                       7.5                  12.5
## 3 Light Oil                       2.3                   3.3
##   SpecificCO2Emission
## 1                 0.7
## 2                11.7
## 3                 2.6
```


1) Commonly viewed as a Bio fuel

2) Bio Energy is produced from biomass derived from any renewable organic plant, including


  

---
### Summary of carbon di oxide levels as per NOAA data


```r
require(graphics)
data(co2, package="datasets")
summary(co2)  
```

```
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##     313     324     335     337     350     367
```


---  { bg: lightgreen}
### Graphical representation of carbon di oxide levels as per NOAA data.
![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3.png) 





