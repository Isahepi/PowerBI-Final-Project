# ** Power BI Project from 365 Financial Analyst **
The final project form the course Power BI have 5 tables
1. dim_currency
2. dim_customer
3. dim_product
4. dim_salesTerritory
5. facts_salesInternet
The ideas was to create a report showing the amounf of sales in the currency selected from the user.

## ** Step by step from 365 Financial Analyst (summarize)**
1. Import tables
2. Crease username inside dim_customer
3. Clean dim_customer from NULL and useless values
4. Import tables
5. Create a #Measure using DAX
6. Create dim_Date with year, month, month name, day of week, quarter, year/quarter
7. Dynamic measire for selected currency, should return the sales amount in the currency selected, no currency if no currency selected
8. Dynamic measure "Sales amount [Selected Currency] vs All currencies", alternative should say "Please select Currency form the Dropdown Menu"
9. Measures for one month, three month, six months previos
10. Measure that will tell us the time the report was last open
11. Header
12. Logo
13. Buttons with clear filter, users, currency, sales territory
14. Measures inside the header
15. Dropdown using bookmarks for users, currency, and sales territory, dropdown shoul have a option search
16. Bookmark for clear filters
17. Import timeline slicer into the dashboard
18. Three boxes sales amount in selected currency, sales amount for all currency in previous month, sales amount for all time for all curreny.
19. Increase the canvas
20. Dinamyc title
21. Line and stacked column chart for showing sales amount in all currencies split by month. Include a dot showing the currency.
22. Dynamic title with Total Products sold in the selected country or total products sold worldwide, should be triggered by the sales territory dropdown button from the header.
23. Number of Products Sold by Country
24. Table with % Total Sales Amount, Sales for previous Month, previous 3 and previous 6 months, include conditional formatting.
