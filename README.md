# ITC Hotels Revenue Analysis Project  

## Overview  
This project aims to explore ITC Hotels' revenue data, focusing on key areas such as revenue optimization, occupancy trends, booking behavior, and cancellations. Using **Power BI**, the analysis is presented through four dashboards designed to provide actionable insights for data-driven decision-making.  

## Dashboards Overview  
### 1. **Revenue Overview Dashboard**  
   - Key financial metrics such as:  
     - **Total Revenue**: ₹28.57M  
     - **ADR (Average Daily Rate)**: ₹6.49K  
     - **RevPAR (Revenue Per Available Room)**: ₹4.32K  
   - Revenue breakdown across different properties and room classes.  
   - Questions Answered:  
     - Which properties are generating the highest revenue?  
     - How do different room categories contribute to overall revenue?  

### 2. **Occupancy Trends Dashboard**  
   - Visualization of occupancy rates for weekdays (42%) vs. weekends (47%).  
   - Comparison of available vs. occupied rooms for each property.  
   - Seasonal trends impacting room occupancy.  
   - Questions Answered:  
     - Are weekends more popular for bookings than weekdays?  
     - How is occupancy distributed across properties?  

### 3. **Booking Patterns Dashboard**  
   - Analysis of booking lead times and average length of stays.  
   - Monthly trends in booking volumes.  
   - Highlights seasonal variations in customer behavior.  
   - Questions Answered:  
     - What is the average lead time for bookings?  
     - Which months see the highest booking activity?  
     - What are the typical stay durations for guests?  

### 4. **Cancellation Analysis Dashboard**  
   - Monthly cancellations and lost revenue trends.  
   - Retained revenue during cancellations.  
   - Focus on June as the month with the highest cancellations.  
   - Questions Answered:  
     - When do cancellations peak, and how much revenue is lost?  
     - How effectively is revenue retained despite cancellations?  

## Data Cleaning and Transformation  
The analysis was preceded by meticulous data preparation steps, including:  
1. **Revenue Adjustment:**  
   - Calculated retained revenue for canceled bookings.  

2. **Ratings Completion:**  
   - Imputed missing ratings based on average values per property.  

3. **Custom Calendar Table:**  
   - Integrated holiday markers and weekend flags.  

4. **Room Capacity Refinement:**  
   - Adjusted room availability data to match booking patterns.  

For a detailed walkthrough of the data cleaning and transformation process, check the attached **documentation (PDF/Word file)** in the repository.

## Insights & Recommendations  
1. **Revenue Drivers:**  
   - ITC Exotica and ITC Palace are top revenue generators.  
   - Elite rooms have the highest contribution to revenue.  

2. **Occupancy Trends:**  
   - Weekends outperform weekdays, suggesting opportunities for weekday promotions.  

3. **Cancellation Management:**  
   - June’s high cancellation rates require better policies and communication strategies.  

4. **Booking Behavior:**  
   - Short lead times and seasonal trends suggest the need for flexible pricing strategies.  

## Tools & Technologies  
- **Power BI**: Interactive dashboards and visualizations.  
- **DAX**: For creating custom measures and calculated fields.  
- **Excel**: Initial exploration and data preparation.  

## File Structure  
- `Dashboard.pbix`: Power BI file containing the interactive dashboard.  
- `Datasets/`: Includes the raw and cleaned datasets used in the project.  
- `Screenshots/`: Visuals of the dashboards for a quick preview.  
- `Documentation/`: Detailed report on the cleaning and transformation process.  

## How to Use  
1. Clone the repository:  
   ```bash  
   git clone 