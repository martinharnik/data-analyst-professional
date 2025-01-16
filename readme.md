# Analysis of Sales Approaches for New Product Line

<b>Background</b>  
Our company has recently introduced a new product line, employing various sales approaches to maximize market penetration and revenue. With an upcoming executive team meeting, there is a critical need to evaluate the effectiveness of these sales methods.

<b>Sales Approaches Overview</b>  
<em>Email</em>: Customers in this segment received an introductory email at the launch of the product line and a follow-up email three weeks later. This approach required minimal effort from our sales team.  
<em>Call</em>: This group of customers was contacted directly by phone, with each call averaging about thirty minutes, representing a significant time investment from our sales team.  
<em>Email and Call</em>: Customers in this category received the initial launch email followed by a phone call a week later. The call lasted about ten minutes per customer, with the email component requiring minimal effort.


<b>Objective</b>  
To conduct a comprehensive analysis of the sales approaches used for the new product line, focusing on customer engagement, revenue generation, and the efficiency of each method over time. This analysis will inform strategic decisions on which sales methodologies to continue, modify, or discontinue.

<b>Key Questions</b>
1. Customer Analysis
    - Determine the number of customers acquired through each sales approach.
    - Explore any discernible differences between the customer groups targeted by each method. 
3. Revenue Analysis
    - Assess the overall revenue generated from the new product line.
    - Analyze the revenue spread for each sales approach, identifying patterns and outliers.
    - Investigate the revenue trajectory over time for each method to discern any trends or fluctuations.
4. Strategic Recommendation
    - Based on the data analysis, recommend which sales approach(es) should be prioritized. Consider factors such as the time investment required by the team, cost-effectiveness, and potential for scalable growth.
    - Highlight any additional insights or observations that could impact future sales strategies, including customer behavior patterns or market responses to each sales approach.

<b>Requirements</b>  
Data Collection and Analysis: Utilize available sales and customer data to conduct your analysis. Apply appropriate statistical tools and methods to uncover insights.  
Presentation of Findings: Prepare a detailed presentation outlining your analysis, findings, and recommendations. The presentation should include data visualizations to illustrate key points and support your conclusions.  
Executive Summary: Include an executive summary that succinctly captures the essence of your findings and recommendations for quick reference by the executive team.


<b>Meta Data</b>  
The data hasn’t been validated, so make sure that you check it against all of the information
in the table before you start your analysis.
| Column Name        | Details                                                                     |
|--------------------|-----------------------------------------------------------------------------|
| week               | Week sale was made, counted as weeks since product launch                    |
| sales_method       | Character, which of the three sales methods were used for that customer     |
| customer_id        | Character, unique identifier for the customer                               |
| nb_sold            | Numeric, number of new products sold                                        |
| revenue            | Numeric, revenue from the sales, rounded to 2 decimal places.               |
| years_as_customer  | Numeric, number of years customer has been buying from us (company founded in 1984) |
| nb_site_visits     | Numeric, number of times the customer has visited our website in the last 6 months |
| state              | Character, location of the customer i.e. where orders are shipped           |