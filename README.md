The central problem addressed by this project is accurately predicting violent crime rates at a city level and understand crime rates relationship with other socio-economic factors. Reliable predictions enable policymakers and law enforcement agencies to implement targeted and effective preventive measures, optimizing resource allocation and community safety.

## Violent Crime Rate in Canadian Cities and Provinces.

Using 6 different datasets from statistics Canada, We are trying to predict the annual violent crime rate in canadian cities. Datasets used are:
- [Incident-based crime statistics, by detailed violations.](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3510017701)
- [Low income entry and exit rates of tax filers in Canada.](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1110002401)
- [Labour force characteristics by census metropolitan area, annual.](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1410046101)
- [Summary characteristics of Canadian tax filers preliminary T1 Family File.](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1110004701)
- [Consumer Price Index, annual average, not seasonally adjusted.](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810000501)
- [Police personnel and selected crime statistics, municipal police services](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3510007701)

Total violent criminal code violations rate per 100k residents is the target variable. Predictors are:
- Unemployment Rate.
- CPI inflation adjusted income.
- Low income immobility rate.
- Police officers per 100,000 population.

The data is per year per census metro area.