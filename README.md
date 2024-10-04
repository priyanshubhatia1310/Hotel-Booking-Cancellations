# Hotel-Booking-Cancellations-Analysis

## Objective

The primary objective of this project is to analyze patterns and trends in hotel booking cancellations to identify key factors contributing to cancellations. This includes examining customer demographics, booking channels, seasonality, and other relevant variables to provide actionable insights. The findings will help the hotel optimize booking management strategies, reduce cancellation rates, and improve revenue forecasting by identifying areas for process improvement and enhancing customer experience.

## Data Cleaning 

Our table now has one less unneeded column thanks to the query editor. At the beginning of the study, there were **32 columns**. However, with the help of the query editor, any unnecessary columns were taken out of the database and opened in an Excel sheet for additional processing. There are currently just **12 columns** in the table.

## Data Processing

We have introduced a few new columns that will be utilized for reporting and analysis once the original columns were removed. We have added two new columns using **nestedif** and the **if condition**.

- **Room Status**: The column designated room type and column reserved room type were used to build this column. This column displays that the client receives the preferred room or any other room.
- **Guest Type**: The purpose of the column is to determine if the clients are a family, a couple, or single.

## Data Anlalysis

- **PivotTable1**: We analyze Total guest and cancelled Bookings based on guest type.

- **PivotTable2**: We analyze Cancelled bookings based on desired and un-desired rooms for the clients.

- **PivotTable3**: We analyze Cancelled Bookings monthwise and the total guest appear monthly.

- **PivotTable4**: To get the Total Booking hotelwise.

- **PivotTable5**: To get the Cancelled bookings hotelwise.

## Data Visualizations

After analyzing the data, we have created a report/dashboard including all the visulation created at the time of analysis. Slicers have been created as **Arrival Year**.

## Project Outcome

Provide different reasons for cancellations of hotel rooms, and with the help of the dashboard, future planning can be done to prevent hotel booking cancellations.
