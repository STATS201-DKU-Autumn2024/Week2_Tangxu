# Annual Maxima Daily Precipitation Data

The HYADES dataset presents a comprehensive archive of station-based annual maxima of daily precipitation, collected from 39,206 ground stations worldwide. Published in *Scientific Data* [1], this dataset spans the period from 1805 to 2023, with station records varying in length from 16 to 200 years. Each record contains essential information on Ground Station ID, Longitude, Latitude, Year, and Annual Maxima of Daily Precipitation in millimeters.

Accessible as open data on Zenodo, HYADES is structured to facilitate extensive data science research on global precipitation patterns, climate trends, and hydrological extremes. Researchers can leverage this dataset to explore variability and changes in extreme precipitation events, study regional precipitation trends, and enhance predictive models in climate science and hydrology.

## References

[1] Vargas Godoy, M.R., Papalexiou, S.M. & Markonis, Y. "HYADES - A Global Archive of Annual Maxima Daily Precipitation," *Scientific Data*, vol. 11, no. 298, 2024. Available: [https://doi.org/10.1038/s41597-024-03109-2](https://doi.org/10.1038/s41597-024-03109-2).

Here is a structured data dictionary for the dataset:
# Data Dictionary for the HYADES Dataset

| **Variable** | **Description**                                                                                                   | **Type**   | **Unit**            |
|--------------|-------------------------------------------------------------------------------------------------------------------|------------|----------------------|
| ID           | Unique identifier for each ground station recording annual maxima of daily precipitation.                        | Integer    | -                    |
| YEAR         | The year when the annual maxima of daily precipitation was recorded.                                             | Integer    | -                    |
| MAX.PRCP     | The highest daily precipitation recorded in a year at the station.                                               | Float      | mm                   |
| LON          | Geographic coordinate that specifies the east-west position of the station.                                      | Float      | Degrees              |
| LAT          | Geographic coordinate that specifies the north-south position of the station.                                    | Float      | Degrees              |

This data dictionary provides an overview of the dataset's main variables, including detailed descriptions, types, and units for each variable.
