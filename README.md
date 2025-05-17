☕️ Coffee Weather Analysis project

For this project, I wore the hat of a data engineer at a Brazil-based weather prediction startup called Curu-Sight. The project explores the relationship between weather patterns and coffee production in Minas Gerais, Brazil, using historical data from 2006 to 2023. The goal was to combine coffee yield data with weather records to identify weather conditions that proved the most favorable for coffee farming, and provide practical, data-driven recommendations to farmers and agricultural stakeholders.

Files
| File                                     | Description                                                     |
| ---------------------------------------- | --------------------------------------------------------------- |
| `weather_data1.csv`, `weather_data2.csv` | Weather data split across two files                             |      
| `coffee_output.csv`                      | Coffee production data                                          |
| `weather_data.csv`                       | Concatenated and cleaned version of weather data                |
| `explore_coffee.ipynb`                   | Notebook for univariate and bivariate analysis on coffee data   |
| `explore_weather.ipynb`                  | Notebook for exploratory analysis on weather data               |
| `analysis.ipynb`                         | Final analysis combining weather and coffee datasets            |
| `README_instructions.md`                 | Guide containing project instructions                           |
| `README.md`                              | Project summary and documentation file written by me            |


Requirements

Python 3.x, pandas, numpy, matplotlib, seaborn, scipy

Key Analyses

  Coffee Data
  
    Univariate analysis of production (e.g. bearing trees, bags per hectare)
    Bivariate correlations between coffee metrics and weather features (Pearson correlation)
    Trend analysis over time
  
  Weather Data
  
    Yearly trend analysis for:
      Average temperature (temp_avg)
      Maximum rainfall (rain_max)
      Minimum and maximum humidity (hum_min, hum_max)
      Average wind speed (wind_avg)
    Pearson correlation between weather variables

Key Insights

  Average temperature and wind speed decreased in Minas Gerais from 2006–2023.
  Average wind speed had the strongest negative impact on coffee production.
  High minimum humidity negatively correlates with coffee production.
  Rainfall and temperature showed non-significant negative trends.


