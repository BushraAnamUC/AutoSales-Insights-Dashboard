# **Automobile Sales Analysis Dashboard**

## Project Outline

- [Project Description](#Project-Description)
- [Key Features of the Dashboard](#key-features-of-the-dashboard)
  - [Yearly Automobile Sales Statistics](#yearly-automobile-sales-statistics)
  - [Recession Period Statistics](#recession-period-statistics)
- [Dataset Details](#Dataset-Details)
- [Project Detail](#Project-Detail)
- [Directory Structure](#directory-structure)
- [Installation and Setup](#installation-and-setup)
- [Future Enhancements](#Future_Enhancements)


---
## **Project Description**
This project analyses historical trends in automobile sales during recession periods. The objective is to provide insights into how sales of XYZAutomotives, a company specialising in automotive sales, were impacted during times of economic downturn.

Using **Dash** and **Plotly**, we created an interactive dashboard that visualises key statistics related to:
1. Yearly Automobile Sales Statistics.
2. Recession Period Statistics.

This dashboard demonstrates various visualisation skills acquired in the project, including line charts, bar charts, and pie charts.

---


## **Key Features of the Dashboard**

### **1. Yearly Automobile Sales Statistics**
- **Yearly Automobile Sales** (Line Chart): Displays the average automobile sales for each year (1980–2013).
- **Total Monthly Automobile Sales** (Line Chart): Displays the total monthly automobile sales for the selected year.
- **Average Vehicles Sold by Vehicle Type** (Bar Chart): Shows the average number of vehicles sold for each vehicle type in the selected year.
- **Total Advertisement Expenditure** (Pie Chart): Represents the total advertising expenditure for each vehicle type in the selected year.

### **2. Recession Period Statistics**
- **Average Automobile Sales Over Recession Periods** (Line Chart): Yearly average automobile sales during recession periods.
- **Average Vehicles Sold by Vehicle Type** (Bar Chart): Displays the average number of vehicles sold for each vehicle type during recession periods.
- **Total Advertising Expenditure Share** (Pie Chart): Represents the share of advertising expenditure by vehicle type during recession periods.
- **Effect of Unemployment Rate on Vehicle Sales** (Bar Chart): Shows the effect of unemployment rates on vehicle sales by type during recession periods.

---

## **Dataset Details**
The dataset used in this project is artificially generated and contains the following variables:
- **Date**: Observation date.
- **Recession**: Binary variable; 1 indicates recession, 0 indicates normal period.
- **Automobile_Sales**: Number of vehicles sold.
- **GDP**: Per capita GDP in USD.
- **Unemployment_Rate**: Monthly unemployment rate.
- **Consumer_Confidence**: Consumer confidence index affecting spending and purchases.
- **Seasonality_Weight**: Seasonal effect weight on sales.
- **Price**: Average vehicle price.
- **Advertising_Expenditure**: Advertising expenditure of the company.
- **Vehicle_Type**: Type of vehicle sold (e.g., Superminicar, Sports).
- **Competition**: Market competition measure.
- **Month, Year**: Extracted from `Date`.

---

## **Project Detail**
1. **Data Loading and Preprocessing**
   - Load the data.
   - Extract `Year` and `Month` from the `Date` column.
   - Filter data for recession and non-recession periods.

2. **Dashboard Design**
   - Use **Dash** for layout and interactivity.
   - Use **Plotly** to create charts.
   - Create callbacks for interactive visualisations.

3. **Visualisations**
   - Line charts for yearly and monthly trends.
   - Bar charts for vehicle sales by type.
   - Pie charts for advertising expenditure.

---

## **Directory Structure**
```
Automobile-Sales-Dashboard/
│
├── app.py                     # Main application script
├── requirements.txt           # Project dependencies
├── README.md                  # Project description
├── data/
│   └── automobile_sales.csv   # Dataset file
├── assets/
│   └── style.css              # Optional CSS for custom styling
└── screenshots/
    └── dashboard_preview.png  # Screenshot of the dashboard (optional)
```
---

## **Installation and Setup**

### **Prerequisites**
1. Python (3.8 or higher) installed.
2. Required libraries installed using:
   ```bash
   pip install -r requirements.txt
### **Steps to Run**

1. Clone the repository:
    ```bash
       git clone <repository-link>
       cd Automobile-Sales-Dashboard
2. Run the application:
       ```bash
          python app.py
3. Open a web browser and navigate to:
     ```bash
     http://127.0.0.1:8050


## **Future Enhancements**

- Include real-world datasets for deeper insights.
- Add user-upload functionality for custom data analysis.
- Enhance the UI with CSS styling.


