# USA_Used_Car_Market

**Data Collection from CarGurus.com**
For data acquisition, a web crawling approach was adopted, leveraging the "Selenium" library's "Webdriver" and "Service" modules. The target website, CarGurus.com, was subjected to analysis. Specific data elements were extracted from each distinct section, encompassing Brand, Make, Year, MilesDriven, Price, EMI, City, and State. The Chrome developer tool facilitated the inspection of the website's HTML code, enabling the identification of relevant tags. This information was harnessed to formulate appropriate regular expressions (Regex) for the data fields. The compiled data was subsequently stored within the "CarguruFinal.db" SQLite database. In total, 923 rows of data were successfully fetched through this process.

**Data Cleaning and Transformation**
To ensure data quality and consistency, SQL queries were employed for data cleaning tasks. This step encompassed identifying and rectifying discrepancies, inaccuracies, and missing values within the dataset.

**Data Analysis Techniques**

**Regression Analysis:**
Python programming was utilized to perform both linear and multiple regression analyses. This involved assessing various statistical metrics, including coefficients, p-values, R-squared, and the potential for omitted variable bias. The results of these analyses were utilized to draw meaningful conclusions regarding the interplay between different variables.

**Data Visualization:**
Python-based visualization techniques were harnessed to create regression line plots and bar graphs. These visual representations were pivotal in elucidating potential factors influencing the dynamics of the used car market.

**Descriptive Analysis:**
Python scripting enabled a comprehensive statistical examination based on geographical divisions (State-wise analysis). This descriptive analysis facilitated a deeper understanding of trends and variations across different states.

In summary, a comprehensive data extraction and analysis process was executed, encompassing web crawling, data cleaning, regression analysis, data visualization, and descriptive statistical analysis. This approach enabled the extraction of insights from the CarGurus.com dataset, shedding light on factors driving the used car market.
