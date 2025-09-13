# City Weather Analysis

This repository contains an R Markdown (`.Rmd`) file and dataset for analyzing and comparing weather data across **Chennai, Delhi, and Mumbai**.

## Objective

The project demonstrates data import, cleaning, manipulation, analysis, and visualization in R. It covers:

* Inspecting raw data
* Handling missing values
* Filtering and feature engineering (Temperature in Fahrenheit)
* Weekly aggregation (Temperature, Humidity, Rainfall)
* Identifying hottest/coldest cities, highest rainfall days, and comparing humidity
* Visualizing weather trends using line, bar, and box plots

## Files

* `City_Weather_Analysis.Rmd` — Main R Markdown file with code and analysis steps
* `city_weather.csv` — Dataset (sample: Chennai, Delhi, Mumbai)
* (Optional) Generated HTML report after knitting

## Requirements

* R (≥ 4.0)
* RStudio (recommended)
* Packages: `tidyverse`, `lubridate`, `ggplot2`, `knitr`

Install required packages:

```r
install.packages(c("tidyverse", "lubridate", "ggplot2", "knitr"))
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
```

2. Open `City_Weather_Analysis.Rmd` in RStudio.
3. Ensure `city_weather.csv` is in the same directory.
4. Knit the file to HTML or Word to generate the report.

## Output

* Line graph: Temperature trends over time (Chennai, Delhi, Mumbai)
* Bar plot: Weekly average rainfall comparison
* Boxplot: Humidity distribution

## Contribution

Feel free to fork this repo and adapt it with your own cities or extended datasets.

## License

This project is for educational purposes and does not include real meteorological data unless provided by the user.
