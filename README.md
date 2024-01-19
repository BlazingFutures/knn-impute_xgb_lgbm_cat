# GoDaddy Microbusiness Density Forecasting

- **Link to the competition**: https://www.kaggle.com/competitions/godaddy-microbusiness-density-forecasting/data

Welcome to the GoDaddy Microbusiness Density Forecasting repository! In this competition, the challenge is to forecast microbusiness activity across the United States, quantified by the density of microbusinesses in US counties. Microbusinesses, often too small or new to appear in traditional economic data, may correlate with broader economic indicators.

## About the Competition
This is a forecasting challenge where participants predict microbusiness density in US counties. The density is measured as microbusinesses per 100 people over the age of 18. Historical economic data are readily available, making it a forecasting competition. Note that forecasts must be static, using information available before the submission period's end.

### Files
- **train.csv**
  - **row_id**: ID code for the row.
  - **cfips**: Unique identifier for each county using the Federal Information Processing System. The first two digits represent the state FIPS code, while the following 3 represent the county.
  - **county_name**: The written name of the county.
  - **state_name**: The name of the state.
  - **first_day_of_month**: Date of the first day of the month.
  - **microbusiness_density**: Target variable - Microbusinesses per 100 people over the age of 18 in the county. Calculated using population data with a two-year lag (e.g., 2021 density using 2019 population figures).
  - **active**: Raw count of microbusinesses in the county (Not provided for the test set).

## External Data Usage
While a substantial amount of data is available about counties, this dataset does not attempt to cover all aspects. Participants are encouraged to utilize external data sources for additional features to enhance forecasting accuracy.


## Contribution Guidelines
Contributions are welcome! Feel free to open issues, submit pull requests, or provide feedback. Let's collaborate to improve the accuracy of microbusiness density forecasts.

Good luck and happy forecasting! 📊
