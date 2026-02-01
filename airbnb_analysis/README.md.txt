# Airbnb Market Analysis: Columbus vs New York

## Author
Parker McGinty

## Project Overview
This project analyzes Airbnb listing data to compare the Columbus, Ohio and New York City markets. The goal is to [briefly describe what decisions your analysis could support].

## Research Questions

1. What owners have many properties and experiencing hosting?
2. How does number of reviews influence price on listings?
3. Is there a relation between room type and number of properties owned by host?
4. Do hosts have multiple listings in the same neighborhoods? 
5. Do hosts keep minimum nights similar for all their listings? 

## Data Source Mapping

| # | Question | Data Needed | Source | Data Type |
|:-:|:---------|:------------|:-------|:----------|
| 1 | [Question 1] | [host_id, listing_id] | [listings.csv] | [Structured]
| 2 | [Question 2] | [price, number_of_reviews] | [listings.csv] | [Structured]
| 3 | [Question 3] | [room_type, host_id, listing_id] | [listings.csv] | [Structured]
| 4 | [Question 4] | [neighborhood, host_id, listing_id] | [listings.csv] | [Structured]
| 5 | [Question 5] | [minimum_nights, host_id, listing_id] | [listings.csv] | [Structured]


## Data Overview
- **Columbus, Ohio:** [2877] listings (as of Sept 26, 2025)
- **New York City:** [36261] listings (as of Dec 4, 2025)
- **Primary data source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)

## Project Status
- [x] Initial data exploration
- [x] Research questions defined
- [x] Data sources mapped
- [ ] Data downloaded and cleaned
- [ ] Analysis complete
- [ ] Visualizations created