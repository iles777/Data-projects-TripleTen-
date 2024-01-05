# Zomato
This project includes research into Zomato’s customers and their ordering behavior for marketing/promotional efforts. Tableau was used to create multiple interactive data visualizations and a simple, easy-to-use interactive dashboards that enables the end user to easily make data-driven decisions.

The interative Tableau dashboard can be found here: https://public.tableau.com/shared/GTGZPMDSS?:display_count=n&:origin=viz_share_link

# Data
There were five tables of data:
1. 'food' table
2. 'menu' table
3. 'orders' table
4. 'restaurant' table
5. 'users' table

# Description
This highly interactive dashboard provides the end user a high level of flexibility to be able to view Zomato’s customer data by any piece of key demographic data, most popular cuisines and time of year the order was placed. This level of flexibility allows this dashboard to remain effective no matter how the customer base changes over time.

This dashboard contains information on who Zomato’s customers are, where they order from, and when they place their orders. Every widget responds to the filters listed vertically starting in the upper right corner. End users are able to filter the data by customer gender, occupation, monthly income, marital status, educational qualifications, month of order date, quarter of order date, and any combination of these filters via the multiple values drop down selection tool for each filter.

Essentially, the end user will be able to create custom subgroups to get specific insight into that subgroups behavior. Whatever combination of filters the end user chooses, they will be provided with the following information: 
* number of customers making up the subgroup
* average age of the customers within the subgroup
* number of orders made by the subgroup
* average number of orders per customer within the subgroup
* total spend of the subgroup
* average spend per customer within the subgroup
* top 15 cuisines ordered from the subgroup
* total number of orders by the subgroup aggregated by month

# Assumptions
* The provided test datasets are accurate, complete, and consistent
* Missing values or inconsistencies are minimal and will not significantly impact the analysis
* The column descriptions accurately reflect the content of each table
* The provided five tables (food, menu, orders, restaurant, users) contain all the necessary information for the chosen analysis and there is no need to use all tables provided
* Zomato's business context and industry trends are considered while interpreting the data

# Process
I performed exploratory data analysis and created a detailed and structured research plan. I then collaborated with a mentor to ensure I was on the right track with my planned analysis. Then I joined the orders, resturant, and users tables to be able to analyze the data.

# Findings
Age, Occupation, and Monthly Income The average age of Zomato’s customers is 24.63 years old. Students make up the majority of Zomato’s customer base accounting for 53% of the total number of customers, 52% of the total number of orders, and 53% of the total spend. Those employed make up the next largest group accounting for 30% of the total number of customers, 31% of total number of orders, and 30% of the total spend. Customers making ₹25000 ($300 USD) or less per month make up nearly two-thirds (66.25%) of total users. These were all expected as its been proven that young people and those with low income make up the majority of all food delivery users (see Zion & Zion’s research)

Consistent Cuisines Total spend and order frequency were used to determine what types of restaurants (cuisine) are most popular with Zomato customers. The following types of restaurants have the five highest order quantity and total spend: North Indian Chinese, Indian, North Indian, Indian Chinese, and Chinese. These stay the top five regardless of how you slice the data demographically.

Time of Year Matters The number of orders changes depending on what time of year it is. February and November have approximately 15% more orders than the annual average. In September, Zomato sees approximately a 30% decrease in orders. Furthermore, Q3 has three of the four months with the lowest number of orders.

Recommendations
* Grow the two largest segments of existing customers (students and employed) by specific & targeted marketing efforts
* Partner with colleges and high-volume employers to provided promotions and incentives for their students/employees to sign up and use Zomato
* Ramp up marketing efforts during their slowest time of year Quarter 3
* Run promotions to encourage new users to sign up and existing customers to spend more and order more often
* Use this data to attract more restaurants to partner with Zomato for their food delivery
* Prioritize restaurants that fall within the top cuisines
* Utilize polls to solicit feedback from existing customers regarding motivations for using Zomato, what restaurants they wish they could order from Zomato but currently can’t to allow your best customers to recommend additional restaurants/cuisines
