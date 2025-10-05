# Weather in Seattle, WA vs Norwich, CT

> Compares the rainfall in Seattle, WA to that in Norwich, CT.

---

## Project Overview

The purpose of this project is to compare the amount of rain in Seattle, WA to that in Norwich, CT. The belief is that it rains more in Seattle. However, I think that Norwich experiences heavier rain than Seattle does, at least at times. Norwich has experienced hurricanes. I plan to explore different ways of measuring whether it rains more in Seattle or in Norwich, but the main question I want to answer is whether over the period from 2018 to 2022 Norwich had more average rainfall than Seattle. 

The data that measures rainfall each day in Seattle and in Norwich was originally obtained from the National Centers for Environmental Information NOAA Climate Data Online Search tool. The key findings were that while it rains more days proportionally in Seattle, the mean daily precipitation is higher in Norwich. This implies that there is more rain in Norwich.

- **Objective:** To compare the rainfall in Seattle, WA to that in Norwich, CT.
- **Domain:** Weather
- **Key Techniques:** Summary statistics and visualizations

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** (https://github.com/brian-fischer/DATA-5100/tree/main/weather) 
                https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND
- **Description:** The datasets are .csv files that include date, precipitation in inches, and location where the data was gathered. There are 1658 entries in the Seattle dataset and 3652 entries in the Norwich dataset.


---

## Analysis

A Jupyter notebook (WeatherData.ipynb) was used to perform the analysis in Python. The code should be run in the order in which it is placed in the notebook.

The steps taken to analyze that data began with cleaning and merging the data and imputing missing precipitation values. The clean data is in the file clean_Seattle_Norwich_weather.csv. Summary statistics and visualizations were produced to compare the precipitation by day and month, including mean daily precipitation, mean monthly precipitation, and proportion of days with precipitation. Statistical tests were performed on the mean monthly precipitation and the proportion of days with precipitation by month.

---

## Results

The key findings were that while it rains more days proportionally in Seattle, the mean daily precipitation is higher in Norwich. This implies that there is more rain in Norwich overall.

---

## Authors

- Your Name - Jennifer Poling (https://github.com/jnplng)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used: Jupyter Notebook; Python: Pandas, Numpy, Matplotlib, Seaborn, Scipy, Statsmodels
- Tutorials referenced: https://github.com/brian-fischer/DATA-5100/tree/main/weather, DATA 5100 weather tutorial

