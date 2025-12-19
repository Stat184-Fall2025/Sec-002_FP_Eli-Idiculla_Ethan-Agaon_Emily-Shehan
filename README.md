**Introduction:**

Our group set out to examine how the Consumer Price Index (CPI) for commonly purchased household foods has changed over the past 20 years and how forecasted trends help explain shifts in food prices over time. To conduct this analysis, we used CPI forecast data published by the United States Department of Agriculture (USDA), which regularly produces inflation forecasts for various food categories as part of its economic research and outlook reports.

These forecasts are widely relied upon by economists, policymakers, and researchers to assess future inflationary pressures in food markets, making them especially valuable for understanding long-term pricing trends. The data set includes key attributes such as CPI item categories, forecast years, and projected percentage changes. To represent a single, central estimate for each forecast, we used the mean forecasted percentage change, which allowed for a clear and consistent comparison across food categories and years.

Because the USDA is a reputable federal agency that follows standardized data collection and reporting practices, this data set can be considered both reliable and authoritative for examining changes in food prices and their broader economic implications.
Research Question

**Research Question** 
How do USDA forecasts of Consumer Price Index (CPI) percent changes differ over time across major food categories—Meats, Fruits and Vegetables, and Dairy Products—and what patterns or trends emerge in these forecasts from 2004 to 2024?

**Data Provenance:**
The data set used in this analysis, CPI Historical Forecast, originates from the United States Department of Agriculture - USDA. The USDA regularly publishes CPI forecasts for various food categories as part of its economic research and outlook reports. These forecasts are widely used by policymakers, economists, and researchers to anticipate inflationary pressures in food markets. The data includes multiple forecast attributes, such as year of forecast and year being forecast. Year of forecast is the year the predicted CPI percent change was created, and year being forecast is when they predict the change to occur. Since the USDA is a reputable federal agency that follows standardized data collection, the data are considered authoritative, reliable, and suitable for economic analysis.

**FAIR and CARE Principles: The dataset largely satisfies the FAIR principles:**

1)  Findable: This dataset is publicly available through USDA publications and online repositories, with clear titles and documentation.

2)  Accessible: This dataset can be downloaded without restrictions and read using standard tools (ex: R or Excel).

3)  Interoperable: This dataset is provided in structured tabular formats that integrate easily with common data analysis software and libraries.

4)  Reusable: This dataset has clear definitions of the variables, consistent formatting, and public licensing allows the data to be reused for multiple analytical purposes.

Overall, this dataset strongly adheres to the FAIR principles, making it suitable for transparent and reproducible research, and a trustworthy data set for our project.

However, the CARE principles - Collective Benefit, Authority to Control, Responsibility, and Ethics - are not as applicable to the context of this data set. This data set does not involve indigenous data or personally identifiable information, and therefore issues surrounding the idea of community authority or consent are minimal. However, this data set does support collective benefit as the data set supports public understanding of inflation and food prices, benefiting society broadly. Additionally, the data set supports responsibility and ethics as the USDA adheres to ethical standards in data reporting and dissemination. While CARE principles are not central to this dataset, the data are used responsibly and ethically in a public-interest context.

**Attributes: The original attributes from the data set include:**

1)  Consumer Price Index Item which identifies the CPI category for the given items in the data set.

2)  Year of Forecast: This is the year in which the forecast was made.

3)  Year Being Forecast: This is the year for which the CPI percent change is being predicted to be in.

4)  Forecast Percent Change: This is the predicted percent change in CPI for the specified category and year.

For our analysis, and due to the magnitude of possible items within the CPI Index Item feature, we will focus on the items meats, dairy, and fruits and vegetables and their associated forecast percent change. For our project, we will create 3 data visualizations and 3 tables to showcase how the USDA predicts the CPI to change for each of these 3 CPI Items. To do this we will evaluate a few things:

1)  We will create graphs to illustrate how the predicted forecast percent change will fluctuate for each CPI item from 2004-2025.

2)  We will create a box and whisker plot for each CPI Item to evaluate the 5 descriptive statistics (Minimum, Q1, Median, Q3, Maximum)

3)  Finally, we will create a scatterplot to plot the mean forecast percent change for each of the CPI items.

To support our graphs, we will partner them with a data table to help us analyze and come to a conclusion based on what each visualization is telling us.
