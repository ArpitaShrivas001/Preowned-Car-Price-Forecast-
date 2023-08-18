# USA_Used_Car_Market
Extracted data from Cargurus.com and utilized data analysis techniques to draw conclusions.  

TARGET DATA SOURCE: CarGurus.Com  
1) Web Crawling
   1) Used “Webdriver” and “Service” modules under the “**Selenium**” library.
   2) Fields fetched from each block:  Brand, Make, Year, MilesDriven, Price, EMI, City, State.
   3) Used **Chrome developer tool** to access the HTML code of the website.
   4) Constructed **Regex** according to the appropriate tags for the data fields using inspect element.
   5) Loaded the fetched data into the **SQLite** database “CarguruFinal.db".
   6) Total rows fetched: 923 

2)  Data Cleaning
   Used SQL queries for data cleaning

4) Data Analysis
      1) Regression Analysis
         Utilized Python to analyze perform linear and multiple regression analysis. Analysed coefficients, p-value, R square and omitted variable bias
         to draw conclusions.
      2) Visulaization
          Utlized Python to plot regression line and bar graphs for potential factors affecting Used car market.
      3) Descrpitive Analysis
         Utlized Python to perform statistical analysis by State. 
