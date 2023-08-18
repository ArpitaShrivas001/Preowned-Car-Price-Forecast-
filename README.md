# USA_Used_Car_Market
Extracted data from Cargurus.com and utilized data analysis techniques to draw conclusions.  

TARGET DATA SOURCE: CarGurus.Com  
1) Web Crawling
   Used “Webdriver” and “Service” modules under the “**Selenium**” library.
   Fields fetched from each block:  Brand, Make, Year, MilesDriven, Price, EMI, City, State.
   Used **Chrome developer tool** to access the HTML code of the website.
   Constructed **Regex** according to the appropriate tags for the data fields using inspect element.
   Loaded the fetched data into the **SQLite** database “CarguruFinal.db".
   Total rows fetched: 923 

2)  Data Cleaning
   Used SQL queries for data cleaning

3) Data Analysis
      1) Regression Analysis
         Utilized Python to analyze perform linear and multiple regression analysis. Analysed coefficients, p-value, R square and omitted variable bias
         to draw conclusions.
      2) Visulaization
          Utlized Python to plot regression line and bar graphs for potential factors affecting Used car market.
      3) Descrpitive Analysis
         Utlized Python to perform statistical analysis by State. 
