# US Superstore Data Analysis Dashboard in PowerBI

#### Introduction
This project involves analyzing a fictional dataset from a fictional US Superstore. The dataset contains detailed information about customer orders, including sales, profits, customer demographics, shipping details, and product categories. The primary objective of using this data is to gain insights into various business operations and performance metrics, which can help in making informed business decisions.

#### Why Use This Data?
The US Superstore dataset provides a comprehensive view of a retail business's operations. By analyzing this data, we can uncover trends, patterns, and insights that are crucial for strategic planning and decision-making. The data analysis covers various aspects such as sales performance, profit margins, customer demographics, and product categories, providing a holistic view of the business.

#### Data Description

The dataset consists of the following columns:
<ul>
  <li>Customer ID: Identifier for customers.</li>
  <li>Customer Name: Name of the customer.</li>
  <li>Order Priority: Priority of the order (e.g., High, Medium, Low).</li>
  <li>Discount: Discount applied to the order.</li>
  <li>Unit Price: Price per unit of the product.</li>
  <li>Shipping Cost: Cost of shipping the order.</li>
  <li>Ship Mode: Mode of shipping (e.g., Regular Air, Delivery Truck).</li>
  <li>Customer Segment: Segment to which the customer belongs (e.g., Small Business, Consumer).</li>
  <li>Product Category: Category of the product (e.g., Furniture, Technology).</li>
  <li>Product Sub-Category: Sub-category of the product.</li>
  <li>City, State, Postal Code: Shipping address details.</li>
  <li>Order Date: Date when the order was placed.</li>
  <li>Ship Date: Date when the order was shipped.</li>
  <li>Profit: Profit from the order.</li>
  <li>Quantity ordered new: Quantity of the product ordered.</li>
  <li>Sales: Total sales amount.</li>
  <li>Order ID: Identifier for the order.</li>
  <li>Total: Total amount for the order.</li>
  <li>Manager: Manager responsible for the order.</li>
</ul>

#### Types of Data Analysis

From this dataset, the following types of analyses can be performed:
##### Sales Analysis:

Identify top-performing products and customer segments.
Analyze sales trends over time.
Explore regional sales performance.

##### Profit Analysis:

Determine the most profitable products and customer segments.
Examine profit trends over time.
Explore regional profit performance.

##### Demographic Analysis:

Acknowledging most active cities based on number of orders made.
Studying the order priorities and the shipment modes for respective priorities.
Examine trend of orders made over time based on different customer segments.

### Steps
#### Data Preparation

##### Upload Data:

Uploaded the Excel file containing the raw data to Power BI Desktop.
###### Data Transformation and Formatting:

Transformed the data to ensure it was in the correct format.
Formatted columns containing prices to currency format.
Removed rows with all blank values.
Calculated necessary measures and added new columns by implementing formulas.
###### Data Cleaning:

Handled missing values by either filling them with appropriate values or removing them.
Ensured consistency in data formats (e.g., dates, currency).
Validated data accuracy by cross-checking with expected ranges and values.

#### Data Visualization

##### Creating Visualizations:

Developed visualizations for Sales Analytics, Profit Analytics, and Order Analytics.
<br>
Used bookmarks and a navigation pane to help viewers navigate through the three segments of the report:
<br>
<ul>
  <li>Sales Analytics: Visualizations include bar charts, line charts, funnel charts, filled map, cards and donut charts to represent sales data.</li>
  <li>Profit Analytics: Visualizations include bar charts, map chart, key influencers, tree map and cards to analyze profitability.</li>
  <li>Order Analytics: Visualizations include bar charts, line charts and stacked bar cahrts, error graphs to analyze orders.</li>
</ul>

Added slicers for regions, states or provinces and filters to provide insights into top sales, top profits, and the number of orders for different product categories and customer segments.
Analyzed trends for sales, profits, and the number of orders over the available period of data.
Customizing the Report:

Downloaded a required theme and made custom changes to fit the visual style of the report.
Ensured that the visualizations were intuitive and easy to understand.
Technical Details
Data Transformation:

Used Power Query Editor to clean and transform data.
Implemented DAX formulas to create calculated columns and measures.
Applied data type transformations for accurate analysis.
Visualization Techniques:

Used bar charts to compare sales and profits across categories.
Employed line charts to show trends over time.
Utilized donut charts to display the proportion of sales and profits by category.
Visual Examples
Here are some screenshots of the key visualizations from the Power BI report:

###### Sales Analytics Dashboard:

![image](https://github.com/user-attachments/assets/04e2e6eb-63ad-4e2d-8c44-5af5c9b10cd3)

###### Profit Analytics Dashboard: 
![image](https://github.com/user-attachments/assets/e9bfb810-030f-4281-a152-2b1ee7252549)

###### Order Analytics Dashboard:
![image](https://github.com/user-attachments/assets/cae0f738-e966-4518-99bd-abdaf540fb8b)

The analysis provided the following key insights:

###### Sales Analytics:

Identified the best-selling products and customer segments that contributed in high sales.
Recognized seasonal sales trends and peak sales periods.
Analyzed regional sales performance to identify high-performing regions.
###### Profit Analytics:

Determined the most profitable products and high profit making customer segments.
Recognized seasonal profit trends and peak profit periods.

##### Conclusion
The analysis of the US Superstore dataset provided valuable insights into the business's sales performance, profitability, and customer demographics. These insights can be used to make data-driven decisions to improve business operations, enhance customer satisfaction, and increase profitability. The visualizations and interactive elements created in Power BI make it easy to explore and understand the data, enabling stakeholders to make informed decisions based on the analysis.



