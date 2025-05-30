# Chinook_Music Sales Analytics Project

## Overview
Developed an interactive 3 excel dashboards to analyze music sales data from the Chinook database. The dashboard enables to explore sales performance, customer and employee behavior, and album/artist success, facilitating data-driven business decisions.


---

## Project Workflow & Tools

Source: Chinook SQL Database (normalized schema with fact and dimension tables)
Tools: Excel, Power Query, Power pivot, DAX (Measures).
Modeling: Star schema with clear relationships between fact and dimension tables (Invoice_line, Invoices, Customers, Employees, Tracks, Albums, Artists, Genres, Playlists)

- **Import & Clean Data Using Power Query**:
Imported all tables (like Invoice, InvoiceLine, Customer, Track, Album, etc.) From SQL Server Database into Excel.
Opened Power Query Editor for each table:
Removed unnecessary columns.
Verified data types (e.g., text, whole number, decimal).
Removed duplicates or blanks if any.
Loaded each table and "Add this data to the Data Model"

- **Data Modeling in Power Pivot**: 
Identified Fact table: InvoiceLine
Identified Dimension tables: Invoice, Customer, Track, Album, Genre, Artist, MediaType, Employee.
Created relationships by dragging keys (One-to-Many)

- **Using SQL Queries in Power Query**: Wrote over 30 analytical queries, including revenue trends, customer patterns, and genre performance
🧠 Used advanced SQL: CTEs, Window Functions, Ranking, Aggregations, and automated KPI reporting using DAX 
---
## Dashboards

![Dashboard Screenshot](https://github.com/HagerSalahRamadan/Chinook_Music-Sales-Analytics-Project/blob/main/1.Sales%20Overview.PNG)
![Dashboard Screenshot](https://github.com/HagerSalahRamadan/Chinook_Music-Sales-Analytics-Project/blob/main/2.Customers%20%26%20Employees%20Insights.PNG)
![Dashboard Screenshot](https://github.com/HagerSalahRamadan/Chinook_Music-Sales-Analytics-Project/blob/main/3.Albums%20%26%20Artists%20Performance.PNG)

- **KPIs (Key Performance Indicators)** :-

   - Total Revenue : ` $2,329` 💰 . 
   - Total Invoices : ` 412` 📦  .
   - Total Tracks Sold : ` 2,240 ` 📦  .
   - Average Sales : `$6` 💰 
   - Max Sales : ` $26` 📈 . 
   - No. Managers : `3`  . 
   - No. Customers : ` 59 ` 👥 . 
  - No. Country : `24` . 
   - No. Artists : `275`  .
   - No. Music Genres : `25`  .
   - No. Albums : `347`  .

   
- **Slicers**: Filter data Slicer >> Year, Quarter, Month.

## Key Insights & Findings

- **Sales & Revenue**
  - USA leads in total revenue.
  - Rock is the top-selling genre.
  - Medium-length tracks (3–6 minutes) outperform others.
  - Sales are consistent month-to-month.

- **Customers & Employees**
  - Top 10 customers generate a large portion of revenue.
  - Employee performance varies significantly.
  - Countries like France and Canada present growth opportunities.

- **Albums & Artists**
  - A few artists and albums account for most sales.
  - Playlist popularity does not always translate to high sales.
  - Some albums show inconsistent sales performance.

---

## Recommendations

- Focus marketing efforts on the US market and popular genres such as Rock.
- Promote tracks with optimal lengths (3–6 minutes).
- Develop VIP loyalty programs for top customers.
- Recognize and replicate strategies from top-performing employees.
- Localize marketing campaigns in emerging countries.
- Invest in top artists and promote underperforming but visible tracks.
---

## Skills Demonstrated

- Advanced SQL querying and data transformation.
- Designing star schema data models.
- Creating KPIs and dynamic measures with DAX.
- Data cleaning and shaping using Power Query.
- Building interactive dashboards and reports in Excel.
- Business storytelling through data visualization.

*This project demonstrates a full analytics lifecycle turning music sales data into strategic business insights.*
---

## Contact
For any questions Contact via email **hagersalah.r39@gmail.com**.



---


