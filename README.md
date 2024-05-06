# End-to-End-Python-Project--Smartprix-Laptops

This repository hosts an end-to-end Python project focused on laptops listed on the Smartprix website. Here's a breakdown of the project:

1. **Web Scraping:** The project starts with web scraping the dataset of laptops from the Smartprix.com website. Utilizing the BeautifulSoup library, the data is extracted from the HTML structure of the website.

2. **Data Cleaning:** The extracted dataset undergoes thorough data cleaning procedures. This involves handling missing values, generating new features from existing ones, and ensuring data consistency. Certain columns have NaN values, with the rating column having the highest number of NaN values. These missing values are retained for further analysis.

3. **Exploratory Data Analysis (EDA):** EDA is performed to gain insights into the dataset and answer various questions. The analysis covers aspects such as the distribution of warranty periods, preferences for RAM and ROM types among different brands, operating system usage patterns, GPU and CPU combinations associated with higher-priced or higher-rated laptops, the impact of core count on prices and ratings, and more.

4. **Insights:** The project uncovers several interesting insights, including:
   - Identification of outlier prices in the dataset.
   - Impact of features like Touchscreen and Gaming on laptop prices.
   - Pricing trends for different laptop brands, with Apple and Microsoft identified as the costliest.
   - Correlation between RAM size and laptop prices.
   - Preference for certain RAM and ROM types among laptop brands.
   - Common GPU and CPU brands across laptops.
   - Analysis of core count and CPU generation's effects on prices and ratings.
   - Distribution of warranty periods among laptop brands.
   - Relationships between features like PPI, price, and ratings.
   - Common OS usage patterns among different laptop brands.

5. **Analysis:**
   - **Touchscreen and Gaming Impact:** Laptops featuring both Touchscreen and gaming features tend to have narrower price ranges, suggesting that these features contribute to increased value and price stability. Conversely, gaming laptops without Touchscreen display a higher incidence of outliers, indicating a broader price range and potential for greater price variability.
   - **Brand Pricing Trends:** Apple and Microsoft emerge as the costliest laptop brands, while HP, Dell, Asus, Samsung, and Acer are more affordable options.
   - **Operating System Influence:** Mac OS laptops exhibit higher price points compared to others, indicating premium pricing associated with the Apple ecosystem. Windows OS laptops are prevalent across brands, with gaming features commonly associated with this OS.
   - **RAM and ROM Preferences:** DDR4 RAM and SSD ROM types are preferred across most brands, reflecting industry trends towards faster and more efficient memory and storage solutions.
   - **GPU and CPU Combinations:** NVIDIA and Intel GPU-CPU combinations are typically associated with higher-priced laptops, highlighting their performance-oriented specifications and premium positioning.
   - **Core Count Analysis:** Laptops with higher core counts tend to have higher prices and ratings, suggesting a positive correlation between core count and perceived value or performance.
   - **Warranty Considerations:** Laptops with longer warranty periods tend to command higher prices, suggesting that consumers perceive greater value and peace of mind with extended warranty coverage.

6. **Conclusion:** The project concludes by summarizing the findings and highlighting potential areas for further investigation.

This project provides a comprehensive demonstration of web scraping, data cleaning, and exploratory data analysis techniques using Python, along with valuable insights into the laptop market.
