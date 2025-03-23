# Project Overview: CreativeYTChannels

**#Objective**
This project is to analyze a YouTube dataset, focusing on Creative YouTube Channels to uncover insights and trends related to engagement metrics, such as impressions, views, and subscribers. The project leverages data cleaning and visualization techniques to derive meaningful correlations and trends from the dataset. Key visualizations, such as bar charts, pie charts, and scatter plots, are used to display various findings, including regional trends, video categories, and channel growth.

**#Key Steps**

**1. Data Cleaning and Transformation**

- Importing necessary libraries (`Pandas` for data manipulation and `matplotlib` for visualization).
- Converting the columns for impressions, video views, and subscribers into a more understandable unit, namely millions (in '000000 format), and rounding to 2 decimal places.
- Extracting the year and month from the channel start date, enabling time-based analysis of trends.
- Dropping unnecessary columns to focus on key metrics (i.e., impressions, video views, subscribers, and start date).

**2. Exploratory Data Analysis (EDA)**
This section involves creating several pivot tables and visualizations to analyze trends in YouTube channels.

- A pivot table to count the number of channels ("youtuber") created each year. This will help analyze the growth of YouTube channels over time.
- A bar plot to visualize the number of channels created per year, helping to see if there is an increasing trend in YouTube channels over time.
- Customizing the bar plot with labels and a rotated x-axis to improve readability.


**3. Regional Insights: Pie Charts**
This section explores how YouTube channels are distributed across different regions.

-  A pivot table is created to count the number of YouTubers per region.
-  Pie charts are generated to display the regional share of YouTube channels, both with and without percentages, providing insights into where channels are most prevalent.


**4. Category-Based Insights: Line Charts**

-  A pivot table is created to sum the total video views for each category, offering insight into which video categories are the most popular.
-  Line plots are generated to visualize the trend in video views across categories, adjusted to represent views in crores for better readability. The x-axis is rotated for better visualization.


**5. Impressions and Views Correlation**
- A pivot table is created to sum impressions across categories.
- A line plot is created to show trends in both video views and impressions for each category, with adjustments made to visualize the data in crores. The plot includes a legend and axis labels for clarity.

**6. Scatter Plot Analysis**

-  Scatter plots are used to visualize the relationship between impressions and video views for channels in Asia and Europe, with legends, axis labels, and titles added for clarity. The scatter plot helps to assess if there's any observable correlation between these two metrics across different regions.

**Insights and Objective Findings**
- An increasing number of YouTube channels are being created annually, as visualized in the bar chart. The rise of digital media is clearly evident.
- The pie charts offer insights into how YouTube is distributed across different regions. Some regions may have higher numbers of content creators, indicating potential markets for content consumption or advertising.
-  The line charts and scatter plots suggest patterns between impressions and video views across categories and regions. For example, certain categories (like "Music" or "Gaming") may have higher impressions and views, while others may not perform as strongly.
-  Video categories such as "Entertainment" or "Gaming" often attract more views and impressions, indicating that these categories are key drivers of engagement.
- Scatter plots comparing Asia and Europe indicate how the performance of YouTube channels may vary across regions, shedding light on regional audience preferences.

**#Conclusion**
This project effectively uses Python’s `Pandas` and `matplotlib` libraries to analyze the performance of Creative YouTube channels. Through cleaning, transforming, and visualizing the data, insights regarding the growth of channels, popular regions, video categories, and correlations between impressions and views are uncovered. The final visualizations, including bar charts, pie charts, and scatter plots, help to convey these insights clearly. This analysis can be extended for more detailed regional marketing strategies or content creation advice based on trends observed.
