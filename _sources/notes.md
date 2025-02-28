# NOAA sst vs OSI SAF sst

OSI SAF
* Spatial resolution: 0.05° latitude × 0.05° longitude.
* Temporal coverage: 2 products per day (00:00, 12:00) since 2016
* Level 3

NOAA:
* Spatial resolution: 0.25° latitude × 0.25° longitude.
* Temporal coverage: Daily values from September 1981 to the present.
* Level 4

# Tutorial

Need to mention https://www.ghrsst.org/ which will be useful for users. Consider reaching out to them about the tutorial.

1. Explain level-1, 2, 3 and 4. Level 2 in SEN3 format, one file per swath. Only focus on L3 and 4. Mention L2 useful for when you need the precise time and location of observations - not on projection, every swath included. Level 3 is binned to 12 hour bins, sometimes averaging multiple measurements. Level 4 has full coverage
2. Show different data sources. Level-3 OSI-SAF, Level-4 NOAA, Met UK might have some too.
3. Show level 3 vs level 4 zoom on gulf stream maybe. Show how this can be an issue in some areas where coverage poor. Would need L3 NOAA data for this...
4. How to plot level 3
5. How to plot level 4
6. Zooming in, extracting values, averaging etc.
