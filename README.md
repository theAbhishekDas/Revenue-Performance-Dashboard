[![](https://github.com/theAbhishekDas/REVENUE-DASHBOARD/blob/main/Asset/01%20Template.png)]()

<h1 align="center"> Revenue Performance Dashboard Analysis </h1>
<p align="center">
<a href="https://www.linkedin.com/in/abhishekdas09/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="supunnanayakkara" height="30" width="40" /></a>
<a href="https://twitter.com/kn1ne09" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="supun.nanayakkaraii" height="30" width="40" /></a>
<a href="https://portfolio-abhishek-das.netlify.app/" target="blank"><img align="center" src="https://github.com/theAbhishekDas/Heart-Disease-Diagnostic-Analysis/blob/main/favicon.ico" alt="supunnanayakkara" height="35" width="35" /></a>
<a href="https://www.instagram.com/_the_happy_das_/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="supun___lk" height="30" width="40" /></a>
</p>
<hr/>
 <img width="440" height="350" align='left' src="https://github.com/theAbhishekDas/REVENUE-DASHBOARD/blob/main/Asset/kisspng-laptop-macbook-pro-computer-hp-pavilion-high-resolution-laptop-png-icon-5ab087a80b6cf7.1954387515215185040468.png" >
Objective of the Query:
The objective of this SQL query is to analyze revenue-related data from a service database in order to derive key performance indicators (KPIs) and insights. Specifically, the query aims to accomplish the following:

1. Determine which region generates the most revenue by summing the total fees from the service data table and grouping them by region from the branch data table.
2. Identify which department generates the most revenue by summing the total fees from the service data table and grouping them by department.
3. Find the top client based on their total revenue contributions.
4. Calculate KPIs such as total revenue, total hours, revenue per region over overall revenue, and month-on-month revenue increase.
<br />
   <br />
Final Outcome:
The final outcome of this SQL query is a set of results that provide insights into revenue generation within the service database. This includes:

- A breakdown of revenue generated by region and department.
- Identification of top clients based on revenue contribution.
- Key performance indicators such as total revenue, total hours, revenue per region over overall revenue, and month-on-month revenue increase. These KPIs help in assessing the financial performance and trends within the service database.

<br />
   <br />

  ![](https://github.com/theAbhishekDas/REVENUE-DASHBOARD/blob/main/Asset/03%20Template.png)

  1. Connect to your data source
- In Power BI, you'll first need to connect to your SQL Server database that contains the [dbo].[services_data] table. This table likely stores your service revenue data.

2. Create the calculated fields
- You may need to create a few calculated fields to derive the specific metrics required for the dashboard. For example, in the image, the Revenue Percentage Increase metric seems to be calculated by comparing the current month's revenue with the previous month's revenue. You can achieve this using a window function like LAG.

3. Build the visuals
- The dashboard contains a variety of visuals including a bar chart, two line charts, and a table. You can build these visuals by dragging the desired fields from the fields pane onto the report canvas.
For instance, to create the bar chart showing “Revenue of Overall by Region”, you would drag the Region field to the axis and sum of Total Revenue field to the values area of the chart.

4. Format the visuals
- Once you have created the visuals, you can format them to improve their readability and aesthetics. You can change the chart titles, axis labels, font sizes and colors as needed.

5.  Add filters and slicers
- You can add filters and slicers to allow users to interact with the dashboard and focus on specific regions, departments or timeframes. For example, you might add a slicer for Region to allow users to view revenue performance for a particular region.
  
[![](https://github.com/theAbhishekDas/Heart-Disease-Diagnostic-Analysis/blob/main/05%20Template1.png)](https://portfolio-abhishek-das.netlify.app/)
