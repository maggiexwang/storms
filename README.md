# Tracking Snow Storms in the Northeast

The March 13 winter storm that bombarded Southern New England set new snowfall records in Boston, Worcester, and Providence. Using storm classification indexes, historical storm data, and climate change studies, this article reveals a pattern of increase in the number of snow storms in the Northeast.  

Standard reporting story as part of course on [Data Journalism](http://www.science.smith.edu/~amcnamara/sds236/) (Smith College, Spring 2018).

## Findings
Throughout the years, the Northeast has seen more snow storms, mainly due to the extreme weather conditions caused by global warming.

The following model showed significance levels of 0.01 for the year and Category 1 (Notable) storms predictors, and 0.05 for Category 2.

```
m_y_strm_level <- lm(n_strm ~ start.year*Category, 
                     data = strm_y_lvl)
```

More exploratory graphs and models can be found in the rsi.rmd file.

## Sources

* Index used in reporting on the severity of snow storms from the [Regional Snowfall Index](https://www.ncdc.noaa.gov/snow-and-ice/rsi/), calculated and published by the [National Oceanic and Atmospheric Administration](http://www.noaa.gov/).  

* Study by [Dr. Judah Cohen](http://www.judahcohen.org/), MIT titled [*Warm Arctic episodes linked with increased frequency of extreme winter weather in the United States*](https://www.nature.com/articles/s41467-018-02992-9#MOESM1).  

* Various reports from news outlets cited as embedded links in the .docx write-out.