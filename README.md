# DroughtObserve (c)
**Sub-national scale drought monitoring and forecasting for Africa and Near East**
`Drought Observe` is a web-based application calledwas developed by the WaterPIP team using open access data and provides historical (past decade) and forecasted (6 months) monthly drought intensity maps at national and sub-national level along with statistics on distribution of major biomes.

The methodology used to develop the data used in DroughtObserve has two major steps – i) preparation of Standardized Precipitation Actual Evapotranspiration Index (SPAEI) from long term monthly water surplus/deficit data ii) applying an auto-regressive model to predict for future months. DroughtObserve uses data from the FAO WAPOR database to compute drought index (version 2). 

The SPAEI is a modified version of the well-known Standardized Precipitation Evapotranspiration Index (SPEI). Instead of precipitation, it uses monthly difference between precipitation and AETI. Using the following formula, the drought index (Di) of a specific month is calculated to represents time series of climatic water balance:

Di = Pi – AETIi

With Pi representing precipitation and AETIi representing actual evapotranspiration of a specific month. The SPAEI for a 12 months (SPAEI12) accumulation period is used to map droughts, which then represents the impact of drought on ecosystems and water resources. The data is then compiled into monthly drought maps and together with spatio-temporal statistics integrated into the dashboard.

The interactive dashboard is publicly available at [https://wateraccounting.github.io/droughtobserve/](https://wateraccounting.github.io/droughtobserve/). Monthly drought maps of the continent starting January 2010 can be visualized by changing the date on the top left-hand corner. When selecting a country, more information on sub-national drought statistics will become available, including a graph showing the timeseries of SPAEI and area statistics of major land cover types. More information can be found [here](https://waterpip.un-ihe.org/droughtobserve).

(c) Made available by the WaterPIP team.
