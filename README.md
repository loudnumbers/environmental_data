# Environmental Data for Sonification

Data sonification is the art and science of turning datasets into sound and music. Learn more at [Ableton.com](https://www.ableton.com/en/blog/sound-the-alarm-data-sonification-as-a-tool-for-climate-action/).

This repository contains a collection of environmental datasets that can be used for sonification. It was compiled by data sonification studio [Loud Numbers](http://www.loudnumbers.net). Direct any questions to [numbersloud@gmail.com](mailto:numbersloud@gmail.com).

If you'd like to push your skills further and meet other sonifiers, check out the [Decibels sonification community](https://decibels.community/).

## Annual

The annual csv file ([download](https://raw.githubusercontent.com/loudnumbers/environmental_data/main/annual.csv)) contains data running from 1959 to 2022 - a timespan of 64 years. It suits shorter sonifications where you might want the story of the data to be clear and obvious.

Here's an explanation of the column names:

### Annual mean CO2 levels in the atmosphere

- **Variable**: co2annual
- **Notes**: Parts per million (ppm). Measured at Mauna Loa volcano, Hawaii.
- **Source name**: Dr. Pieter Tans, NOAA/GML (gml.noaa.gov/ccgg/trends/) and Dr. Ralph Keeling, Scripps Institution of Oceanography (scrippsco2.ucsd.edu/) via NOAA
- **Source link**: [https://gml.noaa.gov/ccgg/trends/data.html](https://gml.noaa.gov/ccgg/trends/data.html)

### Global land and ocean temperature anomaly

- **Variable**: tempannual
- **Notes**: Compared to 1901-2000 mean, degrees Celsius
- **Source name**: NOAA
- **Source link**: [https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series/globe/land_ocean/ann/1/1959-2022](https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series/globe/land_ocean/ann/1/1959-2022)

### Yearly mean total sunspot number

- **Variable**: sunspots
- **Notes**: Obtained by taking a simple arithmetic mean of the daily total sunspot number over all days of each year. Sunspots are unrelated to climate change.
- **Source name**: SILSO, Royal Observatory of Belgium, Brussels
- **Source link**: [https://www.sidc.be/silso/infosnytot](https://www.sidc.be/silso/infosnytot)

### Number of oil spills more than 7 tonnes

- **Variable**: oilspills
- **Notes**: "ITOPF maintains a database of oil spills from tank vessels, including combined carriers, FPSOs and barges. This contains information on accidental spillages of persistent and non-persistent hydrocarbon oil since 1970, except those resulting from acts of war. The data held includes the location and cause of the incident, the vessel involved, the type of oil spilt and the spill amount. For historical reasons, spills are generally categorised by size, <7 tonnes, 7-700 tonnes and >700 tonnes, although the actual amount spilt is also recorded. Information is now held on over 10,000 incidents, the vast majority of which fall into the smallest category i.e. <7 tonnes. Information is gathered from published sources, such as the shipping press and other specialist publications, as well as from vessel owners, their insurers and from ITOPF's own experience at incidents. Historically, information from published sources mostly related to large spills, often resulting from collisions, groundings, structural damage, fires or explosions. In recent decades, however, reporting of smaller spills has improved."
- **Source name**: ITOPF
- **Source link**: [https://www.itopf.org/knowledge-resources/data-statistics/statistics/](https://www.itopf.org/knowledge-resources/data-statistics/statistics/)

### Estimated ozone depleting gas concentration (EESC)

- **Variable**: cfcs
- **Notes**: Parts per billion by volume. Halogen source gases that contribute to ozone depletion are mostly chlorine- and bromine-containing chemicals that have very long lifetimes in the atmosphere. Equivalent effective stratospheric chlorine (EESC) is a convenient parameter we use to estimate the amount of stratospheric ozone depletion due to these compounds. The higher the values of EESC the more chlorine is available for the destruction of ozone. The units of EESC are in parts per billion by volume (ppbv, volume of equivalent chlorine to the the volume of air). Data wasn't available, so five-year quantities were visually estimated from the chart using [https://apps.automeris.io/wpd/](https://apps.automeris.io/wpd/). These values were then fit to a curve using natural cubic spline interpolation, and additional values for the intervening years were calculated.
- **Source name**: NASA Ozone Watch
- **Source link**: [https://ozonewatch.gsfc.nasa.gov/facts/eesc_SH.html](https://ozonewatch.gsfc.nasa.gov/facts/eesc_SH.html)

## Monthly

The monthly csv file ([download](https://raw.githubusercontent.com/loudnumbers/environmental_data/main/monthly.csv)) contains data running from June 1980 to January 2023 - a timespan of 512 months. It suits longer sonifications where you might want things to evolve more gradually.

Here's an explanation of the column names:

### Monthly mean CO2 levels in the atmosphere

- **Variable**: co2monthly
- **Notes**: Parts per million (ppm). Measured at Mauna Loa volcano, Hawaii.
- **Source name**: Dr. Pieter Tans, NOAA/GML (gml.noaa.gov/ccgg/trends/) and Dr. Ralph Keeling, Scripps Institution of Oceanography (scrippsco2.ucsd.edu/) via NOAA
- **Source link**: [https://gml.noaa.gov/ccgg/trends/data.html](https://gml.noaa.gov/ccgg/trends/data.html)

### Global temperature anomaly compared to 1951-1980 mean, °C

- **Variable**: tempmonthly
- **Notes**: Combined Land-Surface Air and Sea-Surface Water Temperature Anomalies (Land-Ocean Temperature Index, L-OTI)
- **Source name:** NASA (GISTEMP model)
- **Source link**: [https://data.giss.nasa.gov/gistemp/](https://data.giss.nasa.gov/gistemp/)

### Arctic sea ice area, millions of square kilometers

- **Variable**: seaice
- **Notes**: The monthly Sea Ice Index provides a quick look at Arctic-wide changes in sea ice. It is a source for consistently processed ice extent and concentration images and data values since 1979.
- **Source name**: US National Snow and Ice Data Center (NSIDC)
- **Source link**: [https://nsidc.org/data/seaice_index/data-and-image-archive](https://nsidc.org/data/seaice_index/data-and-image-archive)
