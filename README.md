# Introduction:

Our group set out to examine how the Consumer Price Index (CPI) for commonly purchased household foods has changed over the past 20 years and how forecasted trends help explain shifts in food prices over time. To conduct this analysis, we used CPI forecast data published by the United States Department of Agriculture (USDA), which regularly produces inflation forecasts for various food categories as part of its economic research and outlook reports.

These forecasts are widely relied upon by economists, policymakers, and researchers to assess future inflationary pressures in food markets, making them especially valuable for understanding long-term pricing trends. The data set includes key attributes such as CPI item categories, forecast years, and projected percentage changes. To represent a single, central estimate for each forecast, we used the mean forecasted percentage change, which allowed for a clear and consistent comparison across food categories and years.

Because the USDA is a reputable federal agency that follows standardized data collection and reporting practices, this data set can be considered both reliable and authoritative for examining changes in food prices and their broader economic implications.

# Exploratory Data Analysis:

#### Research Question

How have USDA forecasted CPI percent changes for meats, dairy products, and fruits and vegetables differed over time, and what do these forecasts reveal about relative price stability and volatility across food categories?

#### Data Provenance:

The data set used in this analysis, CPI Historical Forecast, originates from the United States Department of Agriculture - USDA. The USDA regularly publishes CPI forecasts for various food categories as part of its economic research and outlook reports. These forecasts are widely used by policymakers, economists, and researchers to anticipate inflationary pressures in food markets. The data includes multiple forecast attributes, such as year of forecast and year being forecast. Year of forecast is the year the predicted CPI percent change was created, and year being forecast is when they predict the change to occur. Since the USDA is a reputable federal agency that follows standardized data collection, the data are considered authoritative, reliable, and suitable for economic analysis.

This dataset is particularly well-suited for addressing our research question: how do USDA forecasted CPI percent changes differ across meats, dairy products, and fruits and vegetables, and what do these differences reveal about relative price stability and volatility over time?

#### FAIR and CARE Principles: The dataset largely satisfies the FAIR principles:

1)  Findable: This dataset is publicly available through USDA publications and online repositories, with clear titles and documentation.

2)  Accessible: This dataset can be downloaded without restrictions and read using standard tools (ex: R or Excel).

3)  Interoperable: This dataset is provided in structured tabular formats that integrate easily with common data analysis software and libraries.

4)  Reusable: This dataset has clear definitions of the variables, consistent formatting, and public licensing allows the data to be reused for multiple analytical purposes.

Overall, this dataset strongly adheres to the FAIR principles, making it suitable for transparent and reproducible research, and a trustworthy data set for our project.

However, the CARE principles - Collective Benefit, Authority to Control, Responsibility, and Ethics - are not as applicable to the context of this data set. This data set does not involve indigenous data or personally identifiable information, and therefore issues surrounding the idea of community authority or consent are minimal. However, this data set does support collective benefit as the data set supports public understanding of inflation and food prices, benefiting society broadly. Additionally, the data set supports responsibility and ethics as the USDA adheres to ethical standards in data reporting and dissemination. While CARE principles are not central to this dataset, the data are used responsibly and ethically in a public-interest context.

#### Attributes: The original attributes from the data set include:

1)  Consumer Price Index Item which identifies the CPI category for the given items in the data set.

2)  Year of Forecast: This is the year in which the forecast was made.

3)  Year Being Forecast: This is the year for which the CPI percent change is being predicted to be in.

4)  Forecast Percent Change: This is the predicted percent change in CPI for the specified category and year.

Distinguishing between the year of forecast and the year being forecast is critical for interpreting trends, as it allows us to evaluate how expectations of price changes evolve over time.

#### EDA Focus and Analytical Approach:

For our analysis, and due to the magnitude of possible items within the Consumer Price Index Item attribute, we focus on the categories meats, dairy products, and fruits and vegetables and their associated forecast percent changes. These categories were selected because they represent commonly purchased household foods and differ in supply dynamics, making them appropriate for comparing forecasted price volatility and stability.

To address our research question, we examine how forecasted CPI behavior varies across these three categories using both summary statistics and visualizations. Because multiple forecasts exist for a given year, we use the mean forecasted percent change to represent a central tendency, allowing for consistent comparison across categories and time.

For this project, we create three data visualizations and three tables to evaluate the USDA’s CPI predictions for each category:

We create line graphs to illustrate how forecasted CPI percent changes fluctuate over time for each CPI item from 2004 to 2025, highlighting periods of increased volatility and spread across categories.

We create box-and-whisker plots for each CPI item to evaluate the five descriptive statistics (minimum, Q1, median, Q3, and maximum), which allows us to compare distributional spread and identify which food categories exhibit greater forecast variability.

Finally, we created a scatterplot of the mean forecasted percent change for each CPI item, directly linking the EDA to the research question by comparing long-term average inflation expectations across food categories.

To support our visual analyses, we pair each graph with a corresponding data table to provide quantitative context and strengthen interpretation. Together, these exploratory steps establish early evidence that forecasted CPI behavior differs meaningfully across food categories, setting the foundation for the results and conclusions that follow.
