In this document, I have conducted a comprehensive data processing procedure to refine the transactional data available in the main dataset. The dataset comprises transactional records containing the timestamps and dates of pizza orders.

To optimize data analysis and facilitate insights extraction, I have restructured the data to represent each day's sales in a structured manner. Specifically, I have transformed the data to generate three distinct rows for each day, delineating sales patterns across different times of the day.

The transformation entails the following structure:

* Morning Sales (First Row): This row encapsulates the sales figures for pizzas during the morning hours.
* Afternoon Sales (Second Row): The second row provides insights into pizza sales during the afternoon period.
* Night Sales (Third Row): The third row presents data on pizza sales during the night, including aggregated information such as total sales price and total quantity sold.

So as an illustration, consider a dataset spanning approximately 100 days. By applying the aforementioned data transformation methodology, the resulting dataset would contain a total of 100*3 = 300 rows, each offering granular insights into pizza sales dynamics across various times of the day.

For the Reference Here is the orginal dataset link:  https://www.kaggle.com/datasets/shilongzhuang/pizza-sales
