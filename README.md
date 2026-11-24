# Saudi Real Estate Market Performance Dashboard

A Power BI dashboard analyzing Saudi real estate transactions from 2020 to 2025, built on publicly distributed Ministry of Justice transaction records.

## Data
- Source: Saudi Ministry of Justice public real estate transaction records
- Coverage: 24 quarterly files, 2020–2025 (about 1.39 million transactions)
- Data preparation: the files were cleaned and combined as part of the Saudi Digital Academy / WeCloudData Data Science Bootcamp capstone

## Report pages
**Overview**
- Dynamic KPI cards: transaction value and volume, average price and median price per m², year-over-year comparison
- Transaction value trend by year, quarter and month
- Sales distribution by property type
- Top 10 cities by transaction value
- Slicers for property type, region and date, with a "Clear all slicers" button

**Details**
- City-level matrix table

## Tools
- Power BI Desktop
- DAX measures and a calendar date table
- HTML Content custom visual for the KPI cards, Top 10 cities and matrix table

## Files
- `SRMP_Dashboard.pbix`: the Power BI report file (open with Power BI Desktop)
- `screenshots/`: dashboard page previews

## Screenshots
![Overview](screenshots/overview.png)
![Details](screenshots/details.png)

## Related project
This dashboard is built on the same dataset as the bootcamp capstone, *Saudi Property Transaction Price Prediction*, in which I was responsible for feature engineering.

## Author
Omar Alhejaili, [LinkedIn](https://www.linkedin.com/in/omar-alhejaili)
