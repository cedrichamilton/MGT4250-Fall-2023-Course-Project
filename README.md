# MGT4250 Fall 2023 Course Project
Author: Cedric Hamilton, chamilton19@elon.edu
Author: Max Tarricone, mtarricone@elon.edu

# Project Description
This repo is for the class project of MGT 4250 Fall 2023 at Elon University
Link to visualization application: https://public.tableau.com/views/MGT4250-Fall-2023-Course-Project/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link
<div class='tableauPlaceholder' id='viz1701894377866' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MG&#47;MGT4250-Fall-2023-Course-Project&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MGT4250-Fall-2023-Course-Project&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;MG&#47;MGT4250-Fall-2023-Course-Project&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1701894377866');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1027px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
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


  ## Data description
Data for each visualization can be accessed in the Github Repo as .xls files
The first dataset comes directly from “www.ers.usda.gov/data-products/weekly-retail-food-sales/” Once accessing this link you are able to download excel files with the following columns:
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

The second dataset comes directly from “www.ers.usda.gov/data-products/weekly-retail-food-sales/” Once accessing this link you are able to download excel files with the following columns:

## Interpreting Visualizations
![Dashboard 1](https://github.com/cedrichamilton/MGT4250-Fall-2023-Course-Project/assets/152214811/95b9e17b-8704-4a18-86f1-153f60fa8e6c)

Visualization 1: Heatmap of Regional Sales
Description: A heatmap depicting sales volume across different regions. Darker shades indicate higher sales, and lighter shades show regions with fewer sales. This is used to answer our question by giving insights to sales per region broken down by states to see more or less sales by color. (Lighter green indicates less sales and darker blue indicates lots of sales).
Interactivity: Hover over a region to see exact sales numbers.

Visualization 2: Horizontal Bar Chart Total Unit Sales Per Category 
Description: A multi-line chart where each line represents sales trends over time for a specific region.
Interactivity: Toggle between different regions. Zoom in/out for detailed views of specific timeframes. This provides insight to our question by showing a visual on each category's sales in North America as a whole. By being able to see this is a grand view for North America we can have a rough sense of what sells well all over the country and what doesn't, without the breakdown by region or state.   

Visualization 3: External Factors Influence Bar Graph
Description: A grouped bar graph showing sales spikes (or dips) during specific external events like holidays, weather events, or local festivals. Wen breaking down the total sales per month by state we can differentiate each months sales by state giving double leverage into finding our more to our question and seeing if it can articulate answers around external factors that may exist for each state and month in that state. 
Interactivity: Filter by event type or by region.



## Discussion & Summary
