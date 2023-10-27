# Population change inside California's wildland-urban interface (WUI) (2010-2019)

Shenyue Jia | [jiashenyue.info](jiashenyue.info)
Slade Laszewski | [LinkedIn](https://www.linkedin.com/in/slade-laszewski-8893b91a9)

## Data
### Population data
- U.S. Census American Community Survey yearly estimate (2010-2019)

### WUI boundaries
- [WUI boundary (2023)](https://silvis.forest.wisc.edu/data/wui-change/)
  - Radeloff, V. C., D. P. Helmers, H. A. Kramer, M. H. Mockrin, P. M. Alexandre, A. Bar-Massada, V. Butsic, T. J. Hawbaker, S. Martinuzzi, A. D. Syphard, and S. I. Stewart. 2018. Rapid growth of the U.S. Wildland Urban Interface raises wildfire risk. Proceedings of the National Academy of Sciences, 115(13): 3314-3319.

###  House affordability data
- Esri's calculation using the U.S. Census data for median household income and median home price from census tract to state level
  - Read [this blog article](https://www.esri.com/arcgis-blog/products/esri-demographics/analytics/the-delicate-balance-between-housing-affordability-growth-and-income/) for details
  - Updated every year using the latest demographic data

## Result
- Yearly population for census tracts inside California WUI
  - [Check this folder](https://github.com/jiashenyue/ca-wui-pop/tree/main/pop_wui_tracts)
- Result metrics at census tract level
  - Trend calculated for data from 2010 to 2021 (Mann-Kendall, OLS, Poisson Regression) [link](https://github.com/jiashenyue/ca-wui-pop/blob/main/trend_calculation/pop_trend_2010_2019_WUI_tracts_type.csv)
  - Trend calculated for data from 2010 to 2021 (Mann-Kendall, OLS, Poisson Regression) [link](https://github.com/jiashenyue/ca-wui-pop/blob/main/trend_calculation/pop_trend_2010_2021_WUI_tracts_type.csv)
- An [interactive visualization](https://miamioh.maps.arcgis.com/apps/instant/exhibit/index.html?appid=2849c63b50184b14ae53f5b74142a537) of the housing affordability index and percentage county population living inside WUI
