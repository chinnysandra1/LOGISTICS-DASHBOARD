


# LOGISTICS-DASHBOARD
 Logistics Performance Dashboard – Power BI


A comprehensive analytics dashboard for tracking shipment performance, delays, customers, suppliers, and route behavior.


 ## Project Overview


This project is a complete Logistics Analytics Dashboard built in Power BI.

It provides end to end visibility into shipment operations, helping organizations monitor:

• Shipment volumes

• On time delivery performance

• Delay patterns and causes

• Route and distance insights

• Customer and supplier activity

• Driver and vehicle performance



The dashboard is designed to support decision making across logistics, supply chain, and operations teams.



 ### Dataset Description



The dataset contains transactional shipment records with operational and geospatial fields.



#### Key Columns

• Booking ID

• Customer Name / Supplier Name

• Shipment Type

• Booking Date

• Planned ETA / Actual ETA

• Trip Start Date / Trip End Date

• Origin & Destination Locations (with coordinates)

• Transportation Distance (KM)

• Vehicle Type

• Minimum KM To Be Covered Daily

• Driver Name & Mobile

• On Time Indicator (Yes/No)

• GPS Provider & Real-Time Ping




### Business Objectives

• Track logistics performance across all shipments

• Identify customers and suppliers with the highest activity

• Analyze factors contributing to shipment delays

• Compare planned vs actual delivery performance

• Monitor routes, distance, and driver activity

• Improve operational efficiency 



 ### Dashboard Structure



The dashboard contains 3 main pages:




### 1. Overview Page



A high level summary focusing on operational performance:

• Total shipments

• On time delivery %

• Average delivery duration

• Total delays

• Distance traveled

• Shipment trends

• Busiest dates


<img width="1208" height="677" alt="Image" src="https://github.com/user-attachments/assets/9318bf24-13f0-419a-94c4-bed4b6789b62" />



### 2. Delay Insights Page



This page answers: “Where and why do delays happen?”

• Delay count by supplier

• Delay count by customer

• Delay by vehicle type

• Delay by route distance

• Planned vs actual delivery variance

• Average delay hours

• Root-cause analysis visuals

• Trend of delays over time

<img width="1208" height="664" alt="Image" src="https://github.com/user-attachments/assets/91e5e6ad-f93c-4009-bc3d-272ef3eddf3f" />





### 3. Customer & Supplier Matrix Page



A comparative analysis dashboard:

• Count of customer

• Count of supplier

• Shipments per customer

• Shipment performance matrix

• On time % by customer & supplier

• Delay frequency per customer


<img width="1166" height="605" alt="Image" src="https://github.com/user-attachments/assets/b0ce2600-f217-485c-b27c-89260e2589d1" />




### Key Insights Generated

• Top customers by shipment volume

• Suppliers with the highest delay rates

• Routes contributing to repeated delays

• Correlation between vehicle type and delivery performance

• Distance patterns affecting ETA accuracy

• On time performance benchmarks

• Outliers in trip duration and travel behavior


### Technical Steps



 1. Data Cleaning (Power Query)

• Removed null values from date fields


• Extracted date parts (Month, Day, Quarter)

•completed missing date columns with corresponding ETA and ATA Dates

• Converted data types (dates, whole numbers, decimals)



2. Data Modeling



Star-schema style:

• Fact Table – Shipment transactions

• Dimension Tables – Date, Customer, Supplier, Vehicle



Relationships based on:

• Booking ID

• Customer Name

• Supplier Name

• Trip dates



3. DAX Measures Created

• Total Shipments

• On-Time Delivery %

• Number of Delays

• Average Delay Duration

• Shipments per Customer

• Shipments per Supplier

• Distance KPIs

• Performance benchmarks


 ### Tools Used

• Power BI – Dashboard design & DAX

• Power Query – Data cleaning

• Excel / CSV – Dataset format

• GitHub – Documentation & portfolio hosting



 ### What I Learned

• End to end Power BI workflow

• Designing multi-page business dashboards

• Building KPIs for real-world logistics operations

• Using coordinates for route visualizations

• Creating insight summaries and performance matrices

• Communicating findings clearly



Interact with the dashboard here👇

https://tinyurl.com/2u4mvt3s

If you’d like to collaborate or need help analyzing your logistics operations, feel free to reach out:

#### Email:chinnysandra77@gmail.com

#### Sandra Amalu – Data Analyst
