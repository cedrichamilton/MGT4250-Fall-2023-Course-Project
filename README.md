# MGT4250 Fall 2023 Course Project
Author: Cedric Hamilton, chamilton19@elon.edu

Author: Max Tarricone, mtarricone@elon.edu

# Project Description
This repo is for the class project of MGT 4250 Fall 2023 at Elon University

Link to Tableau Public visualization application: https://public.tableau.com/views/MGT4250-Fall-2023-Course-Project/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link

### Questions of interest:
- How do sales of products vary across different regions?
- What external factors (like weather, holidays, or local events) influence these regional sales patterns?

### Reasoning:
Understanding regional sales patterns is extremely important to businesses, as it directly influences inventory management, marketing strategies, and supply chain logistics. Regions experiencing higher sales may require increased stock, while those with lower sales may signal the need for targeted marketing campaigns or a reevaluation of product-market fit. Furthermore, acknowledging the impact of external factors enables anticipatory business strategies, ultimately optimizing sales and enhancing customer satisfaction. Weather conditions can significantly affect the sales of seasonal products; a cold wave may drive up heater sales in one region, while a heatwave could boost air conditioner sales in another. Additionally, holidays, deeply rooted in regional cultures and traditions, exert a substantial influence on sales spikes. For instance, the Chinese New Year can result in a surge in sales in East Asia, while Black Friday has a significant impact on sales in North America. Furthermore, local events such as festivals, sports events, or conventions can lead to temporary sales boosts. Understanding these regional sales patterns and the external factors that shape them is essential for businesses to accurately forecast demand, manage inventory, and tailor their marketing efforts effectively.

References:
Federal Reserve Bank of San Francisco. (2022). Impact of weather on retail sales. Economic Letter. Retrieved from https://www.frbsf.org/economic-research/publications/economic-letter/2022/august/impact-of-weather-on-retail-sales/

Abdul, R. (Date not specified). Regional sales analysis of a retail company based in the United States. Medium. Retrieved from https://medium.com/@Riabdulm/regional-sales-analysis-of-a-retail-company-based-in-the-united-states-1b9a298e3533

C+R Research. (Date not specified). Regional differences do matter. Retrieved from https://www.crresearch.com/blog/regional-differences-do-matter/

Corsi, A., Mueller Loose, S., & Lockshin, L. (2012). The sales impact of regional and environmental in-store promotions. Wine & Viticulture Journal. Retrieved from https://www.marketingscience.info/wp-content/uploads/2016/07/Corsi-2012-WVJ-6400.pdf


  # Data description
Data for each visualization can be accessed via the link below in the Github Repo as .xlsx files ("StateAndCategory (1).xlsx" and "NationalTotalAndSubcategory (1).xlsx")

https://github.com/cedrichamilton/MGT4250-Fall-2023-Course-Project/blob/49faa84bcd3eefd872413e1bf20ab04e6f2d8a1d/StateAndCategory%20(1).xlsx

https://github.com/cedrichamilton/MGT4250-Fall-2023-Course-Project/blob/6a626b85c51fc0886d1d52bd139bd38d9de3abd2/NationalTotalAndSubcategory%20(1).xlsx

The first dataset comes directly from “www.ers.usda.gov/data-products/weekly-retail-food-sales/” Once accessing this link you are able to download "StateAndCategory (1).xlsx" with the following columns:

1. Date: Week ending
2. State: State
3. Category: Food category
4. Dollars: Total value of sales
5. Dollars last year: Total value of sales, same week last year
6. Dollars 3 years ago: Total value of sales, same week 3 years ago (available starting May 2022 with data beginning October 3, 2021)
7. Unit sales: Total units sold, any size
8. Unit sales last year: Total units sold, any size, same week last year
9. Unit sales 3 years ago: Total units sold, any size, same week 3 years ago (available starting May 2022 with data beginning October 3, 2021)
10. Percent change dollars 1 year: Change in sales value since same week last year, as a percent of last year's sales value
11. Percent change units 1 year: Change in units sold of any size since same week last year, as a percent of last year's units sold

The second dataset comes directly from “www.ers.usda.gov/data-products/weekly-retail-food-sales/” Once accessing this link you are able to download "StateAndCategory (1).xlsx" with the following columns:

1. Date: Week ending
2. Category: Food category
3. Subcategory: Food subcategory
4. Dollars: Total value of sales
5. Dollars last year: Total value of sales, same week last year
6. Dollars 3 years ago: Total value of sales, same week 3 years ago (available starting May 2022 with data beginning October 3, 2021)
7. Unit sales: Total units sold, any size
8. Unit sales last year: Total units sold, any size, same week last year
9. Unit sales 3 years ago: Total units sold, any size, same week 3 years ago (available starting May 2022 with data beginning October 3, 2021)
10. Share: Category share of total dollar sales
11. Share last year: Category share of total dollar sales, same week last year
12. Share 3 years ago: Category share of total dollar sales, same week 3 years ago (available starting May 2022 with data beginning October 3, 2021)
13. Percent change dollars 1 year: Change in sales value since same week last year, as a percent of last year's sales value
14. Percent change units 1 year: Change in units sold of any size since same week last year, as a percent of last year's units sold
15. Percent change share 1 year: Change in share since same week last year, as a percent of last year's share
16. Percent change dollars 3 years: Change in sales value since same week 3 years ago, as a percent of sales value 3 years ago (available starting May 2022 with data beginning October 3, 2021)
17. Percent change units 3 years: Change in units sold of any size since same week 3 years ago, as a percent of units sold 3 years ago (available starting May 2022 with data beginning October 3, 2021)
18. Percent change share 3 years: Change in share since same week 3 years ago, as a percent of share 3 years ago (available starting May 2022 with data beginning October 3, 2021)



# Interpreting Visualizations
![Dashboard 1](https://github.com/cedrichamilton/MGT4250-Fall-2023-Course-Project/assets/152214811/95b9e17b-8704-4a18-86f1-153f60fa8e6c)

### Heatmap of Regional Sales
Description: A heatmap depicting sales volume across different regions. Darker shades indicate higher sales, and lighter shades show regions with fewer sales. This is used to answer our question by giving insights to sales per region broken down by states to see more or less sales by color. (Lighter green indicates less sales and darker blue indicates lots of sales).
Interactivity: Hover over a region to see exact sales numbers.

### Total Sales Per Month by State
Description: A multi-line chart where each line represents sales trends over time for a specific region.
Interactivity: Toggle between different regions. Zoom in/out for detailed views of specific timeframes. This provides insight to our question by showing a visual on each category's sales in North America as a whole. By being able to see this is a grand view for North America we can have a rough sense of what sells well all over the country and what doesn't, without the breakdown by region or state.   

### Total Sales Per Category
Description: A bar graph showing sales spikes (or dips) during specific external events like holidays, weather events, or local festivals. Wen breaking down the total sales per month by state we can differentiate each months sales by state giving double leverage into finding our more to our question and seeing if it can articulate answers around external factors that may exist for each state and month in that state. 
Interactivity: Filter by event type or by region.



# Discussion & Summary
Article:
https://www.sciencedirect.com/science/article/abs/pii/S0143622823001650

Article Summary:
This study compares, using geostatistical analysis and spatial regression, the trade area composition of typical supermarkets and specialist food chains in the United States. Along with demographics, it focuses on customer lifestyles and the competitive environment. The results indicate that specialist grocery stores are more likely to be found in locations with a greater proportion of people who commute by bicycle or foot, as well as a larger concentration of health and fitness facilities. Furthermore, compared to regular supermarkets, specialist food stores are more likely to be situated in trade areas with higher levels of competition. Grocery companies, urban planners, and shopping center developers can all benefit from these findings' practical implications.

GPT-4 Query:
How do sales of products vary across different regions? What external factors (like weather, holidays, or local events) influence these regional sales patterns?

Visualizations:



