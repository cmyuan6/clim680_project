# Analyzing the Impact of ENSO Phases on Precipitation Patterns
By Casey Yuan
# Introduction
Precipitation is the most important and active variable associated with atmospheric circulation in weather and climate studies. Understanding the connection between climate trends and precipitation patterns is essential for managing water resources and predicting extreme weather events. One key factor driving climate variability is the El Niño-Southern Oscillation (ENSO), which significantly impacts global precipitation and temperature patterns. In this project, I explore the impact of ENSO phases (El Niño, La Niña, and Neutral) on precipitation patterns using the University of Delaware’s long-term precipitation data and the ENSO climate index.
# Data
The datasets used in my project are:
## University of Delaware Terrestrial Precipitation, from 1900/01 to 2014/12
Cort Willmott and Kenji Matsuura from the University of Delaware compiled data from a wide range of stations. The UDEL-TS dataset includes rain gauges from several sources, such as the Global Historical Climatology Network, the Daily Global Historical Climatology Network, the Atmospheric Environment Service archive, the Hydrometeorological Institute, GC-Net, and other regional and global networks. The GPCC and CRU-TS datasets provide similar temporal coverage and resolution, but they primarily rely on data from national meteorological agencies, the WMO, and the Food and Agriculture Organization. Unlike UDEL-TS and CRU-TS, which use cross-validation and outlier detection, the GPCC dataset requires at least 10 years of continuous data for each station to be included.
It is a global gridded monthly land precipitation and temperature dataset.
## ENSO Precipitation Index, from 1979 to 2023
Time series that uses rainfall data from the Tropical Pacific to characterize ENSO events. This climate index measures the precipitation anomalies associated with El Niño and La Niña conditions. The index is widely used in climate studies to track ENSO phases and their associated precipitation variations across the Pacific region.
# Results and Analyses
## Climatology

![A panel plot of the climatology of monthly terrestrial precipitation](https://github.com/cmyuan6/clim680_project/blob/main/monthly.png)

A panel plot of the global climatology of monthly averaged precipitation was created using the University of Delaware data. The precipitation levels are represented with a color gradient: yellow for low precipitation, orange to red for moderate precipitation, and purple to blue for high precipitation. The analysis reveals that tropical regions, such as the Amazon, Central Africa, and Southeast Asia, experience consistently high precipitation throughout the year, especially near the equator. In the Northern Hemisphere, higher precipitation is observed in the summer months (June–August), with a decline in winter (January–February). The Southern Hemisphere shows increased precipitation during its summer months (December–February) and lower levels during winter (June–August). Deserts, including the Sahara, Arabian Peninsula, and Australia, exhibit low precipitation year-round. Monsoon patterns, particularly in South Asia and parts of Africa, contribute to significant increases in precipitation between June and September. Regions like South America and parts of Africa display distinct wet and dry seasons, with noticeable shifts in precipitation levels throughout the year.

## Composites

![composites](https://github.com/cmyuan6/clim680_project/blob/main/composite.png)

Composite analysis is performed on global precipitation anomalies with the ENSO index to observe the influence of El Niño, La Niña, and Neutral phases on precipitation patterns. There are three phases: El Niño (positive) - 80, La Niña (negative) - 380, and Neutral - 78. 

For El Niño events, positive precipitation anomalies were observed in the eastern Pacific Ocean and parts of South America, while negative anomalies were found in regions such as Australia, Southeast Asia, and parts of Africa. In contrast, La Niña events displayed the opposite pattern, with increased precipitation in Australia, Southeast Asia, and parts of Africa, and decreased precipitation in the eastern Pacific and South America. During Neutral conditions, precipitation anomalies were generally minimal, with most regions experiencing near-average precipitation. ENSO changes atmospheric circulation and impacts precipitation and temperature globally. In the graph, El Niño tends to bring wetter conditions to the eastern Pacific and drier conditions to parts of Asia and Australia, while La Niña has the reverse effect. The Neutral phase, in contrast, presents minimal deviations from typical precipitation patterns, indicating that ENSO-induced precipitation changes are most pronounced during El Niño and La Niña events.

![difference](https://github.com/cmyuan6/clim680_project/blob/main/difference.png)
![difference](https://github.com/cmyuan6/clim680_project/blob/main/differences%20neg.png)

Two plots were generated to show the mean differences between positive and negative composites, with areas of statistical significance indicated by the 95% confidence interval. The plots highlight regions where the differences in composite precipitation between the two event types are statistically significant.

## Correlation

![correlation](https://github.com/cmyuan6/clim680_project/blob/main/correlation.png)

With correlation, we see how ENSO is related to changes in precipitation. Positive correlations indicate that precipitation increases during El Niño events, when values are higher and decreases during La Niña events when values are lower. Negative correlations show the opposite pattern, where precipitation decreases during El Niño and increases during La Niña. Regions with values near zero suggest little to no relationship between precipitation anomalies and ENSO.

In the tropical Pacific Ocean, strong positive correlations in the central and eastern Pacific reflect increased precipitation during El Niño, while negative correlations in the western Pacific indicate reduced precipitation. Along the western coast of South America, wetter conditions are associated with El Niño events. In contrast, parts of the Amazon basin show negative correlations, signaling drier conditions during the same periods.

Southeast Asia and Australia are dominated by negative correlations, indicating less precipitation during El Niño. In Africa, eastern regions experience wetter conditions during El Niño, as shown by positive correlations, whereas southern Africa tends to be drier, reflected in negative correlations. North America presents a mixed pattern, with positive correlations in the southern U.S. and parts of Mexico, and negative correlations in the northern U.S. and Canada. Europe exhibits generally weak correlations, suggesting minimal direct influence from ENSO.

The strongest ENSO-related impacts on precipitation are concentrated in the tropics and subtropics, where atmospheric circulation is most affected. In polar regions, correlations are weak or nonexistent, indicating limited ENSO influence.
