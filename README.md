Data Analysis

Our group set out to examine how the Consumer Price Index (CPI) for commonly purchased household foods has changed over the past 20 years and how forecasted trends help explain shifts in food prices over time. To conduct this analysis, we used CPI forecast data published by the United States Department of Agriculture (USDA), which regularly produces inflation forecasts for various food categories as part of its economic research and outlook reports.

These forecasts are widely relied upon by economists, policymakers, and researchers to assess future inflationary pressures in food markets, making them especially valuable for understanding long-term pricing trends. The dataset includes key attributes such as CPI item categories, forecast years, and projected percentage changes. To represent a single, central estimate for each forecast, we used the mean forecasted percentage change, which allowed for a clear and consistent comparison across food categories and years.

Because the USDA is a reputable federal agency that follows standardized data collection and reporting practices, this dataset can be considered both reliable and authoritative for examining changes in food prices and their broader economic implications.


Data Provenance

The dataset used in this analysis,
CPIHistoricalForecast, originates from the United States Department of Agriculture (USDA). The USDA regularly publishes CPI forecasts for various food categories as part of its economic research and outlook reports. These forecasts are widely used by policymakers, economists, and researchers to anticipate inflationary pressures in food markets.
The data include multiple forecast attributes (such as prediction intervals), CP| item categories, forecast years, and forecasted percent changes. For this analysis, only the midpoint of the prediction interval was used to represent the central forecast estimate, ensuring consistency and interpretability.
Because the USDA is a reputable federal agency that follows standardized data collection and dissemination practices, the data are considered authoritative, reliable, and suitable for economic analysis.

FAIR Principles

The dataset largely satisfies the FAIR principles:
• Findable: The data are publicly available through USDA publications and online repositories, with clear titles and documentation.
• Accessible: The data can be downloaded without restrictions and read using standard tools (e.g., R, Excel).
• Interoperable: The dataset is provided in structured tabular formats that integrate easily with common data analysis software and libraries.
• Reusable: Clear variable definitions, consistent formatting, and public licensing allow the data to be reused for multiple analytical purposes.
Overall, the data strongly adhere to FAIR principles, making them suitable for transparent and reproducible research.
CARE Principles
The CARE principles (Collective Benefit, Authority to Control, Responsibility, and Ethics) are less directly applicable in this context. The dataset does not involve Indigenous data or personally identifiable information, and therefore issues of community authority or consent are minimal. However:
Collective Benefit: The data support public understanding of inflation and food prices, benefiting society broadly.

Responsibility and Ethics: As a federal economic dataset, the USDA adheres to ethical standards in data reporting and dissemination. While CARE principles are not central to this dataset, the data are used responsibly and ethically in a public-interest context.
Original Attributes from the Dataset
consumer_price_index_item: Identifies the CPI category (Meats, Fruits and Vegetables, Dairy Products).


year_of_forecast: The year in which the forecast was issued.


year_being_forecast: The year for which the CPI percent change is being predicted.


forecast_percent_change: The predicted percent change in CPI for the specified category and year.


Filtered and Derived Attributes
Midpoint forecast selection: The attribute variable was filtered to include only the midpoint of the prediction interval, which was a deliberate analytical choice to focus on the central forecast estimate rather than uncertainty bounds.


Tidied structure: Variable names were standardized using clean_names() to improve readability and consistency across analyses.


These attributes allow for temporal trend analysis, category comparisons, and visualization of long-term CPI forecast behavior across food sectors
Conclusion
By preparing and tidying the USDA CPI forecast data, this exploratory analysis establishes a clean and interpretable foundation for visual exploration. The following sections use time-series visualizations to examine forecasted CPI percent changes across food categories, highlighting trends, volatility, and category-specific patterns that inform broader discussions of food price inflation.
