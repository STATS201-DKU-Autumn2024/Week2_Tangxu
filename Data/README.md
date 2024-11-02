# Annual Maxima Daily Precipitation Data

The HYADES dataset presents a comprehensive archive of station-based annual maxima of daily precipitation, collected from 39,206 ground stations worldwide. Published in *Scientific Data* [1], this dataset spans the period from 1805 to 2023, with station records varying in length from 16 to 200 years. Each record contains essential information on Ground Station ID, Longitude, Latitude, Year, and Annual Maxima of Daily Precipitation in millimeters.

Accessible as open data on Zenodo, HYADES is structured to facilitate extensive data science research on global precipitation patterns, climate trends, and hydrological extremes. Researchers can leverage this dataset to explore variability and changes in extreme precipitation events, study regional precipitation trends, and enhance predictive models in climate science and hydrology.

## References

[1] Vargas Godoy, M.R., Papalexiou, S.M. & Markonis, Y. "HYADES - A Global Archive of Annual Maxima Daily Precipitation," *Scientific Data*, vol. 11, no. 298, 2024. Available: [https://doi.org/10.1038/s41597-024-03109-2](https://doi.org/10.1038/s41597-024-03109-2).

With the revised data dictionary below.
# Data Dictionary for HYADES32 Dataset

| **Variable**         | **Description**                                                                                                   | **Type**   | **Unit**            |
|----------------------|-------------------------------------------------------------------------------------------------------------------|------------|----------------------|
| Ground Station ID    | Unique identifier for each ground station recording annual maxima of daily precipitation.                        | Integer    | -                    |
| Longitude            | Geographic coordinate that specifies the east-west position of the station.                                      | Float      | Degrees              |
| Latitude             | Geographic coordinate that specifies the north-south position of the station.                                    | Float      | Degrees              |
| Year                 | The year when the annual maxima of daily precipitation was recorded.                                             | Integer    | -                    |
| Annual Maxima        | The highest daily precipitation recorded in a year at the station.                                               | Float      | mm                   |

# Summary Statistics Variables

| **Variable**         | **Description**                                                                                                   | **Type**   | **Unit**            |
|----------------------|-------------------------------------------------------------------------------------------------------------------|------------|----------------------|
| Record Length        | Duration of data collection at each station, ranging from 16 to 200 years.                                       | Integer    | Years                |
| Trend                | Trend in annual maxima of daily precipitation per year.                                                           | Float      | mm/year              |
| Median               | Median of annual maxima values across the stations.                                                               | Float      | mm                   |
| Mean                 | Average of annual maxima values across the stations.                                                              | Float      | mm                   |
| SD                   | Standard deviation of annual maxima values across the stations, indicating variability.                           | Float      | mm                   |
| L-Scale              | L-moment scale, a statistical measure representing variability in the annual maxima values.                       | Float      | -                    |
| L-Skewness           | L-moment skewness, indicating the asymmetry of the annual maxima distribution.                                   | Float      | -                    |
| L-Kurtosis           | L-moment kurtosis, indicating the peakedness or flatness of the annual maxima distribution.                       | Float      | -                    |
