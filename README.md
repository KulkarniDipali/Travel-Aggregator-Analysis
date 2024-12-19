# Travel-Aggregator-Analysis
This repository contains a Python project that performs an analysis on bookings and sessions data to extract insights, such as:

Distinct counts of bookings, sessions, and searches.
Analysis of booking distributions across different days of the week.
Correlation heatmap showing relationships between numeric variables.
Device usage trends by service and quarterly device trends.
Analysis of oBSR (Online Booking Search Rate) by month and day of the week.
The project also visualizes these insights through various charts and graphs to aid decision-making and business intelligence.

Table of Contents
Introduction
Data Files
Installation
Usage
Visualizations
Licenses
Introduction
This project leverages Python’s data analysis libraries such as Pandas, Matplotlib, and Seaborn to process and analyze booking and session data. The primary goals of the analysis include:

Understanding booking patterns by day of the week.
Identifying trends in bookings and search behavior.
Understanding customer preferences regarding device usage.
Investigating correlations between various booking attributes.
Data Files
This project uses two CSV data files:

Bookings.csv: Contains details related to bookings such as booking ID, service name, INR amount, etc.
Sessions.csv: Contains session data including session ID, search ID, customer ID, search time, etc.
Ensure you have these CSV files in the appropriate folder when running the code.

Installation
To run this project locally, you need to have Python 3.x installed on your machine, along with the required libraries.

Required Libraries
You can install the necessary libraries using pip. Run the following command in your terminal:

bash
Copy code
pip install pandas matplotlib seaborn
Usage
Clone this repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/yourusername/booking-session-analysis.git
Place your Bookings.csv and Sessions.csv files in the project folder (or update the file paths in the code to match where your files are located).

Run the booking_analysis.py script:

bash
Copy code
python booking_analysis.py
This will execute the analysis and generate visualizations and insights, including:

Pie chart for bookings distribution by day of the week.
Bar plots for the average oBSR (Online Booking Search Rate) by month and day of the week.
Correlation heatmap for the numerical attributes in the bookings dataset.
A stacked bar plot of quarterly trends by device type.
Visualizations
The following visualizations are generated and saved as PNG files in the project directory:

Bookings Distribution by Day of the Week: A pie chart displaying the distribution of bookings across the days of the week.
Average oBSR by Month: A bar plot showing the average oBSR for each month.
Average oBSR by Day of the Week: A bar plot showing the average oBSR for each day of the week.
Quarterly Trends by Device Type: A stacked bar plot showing trends in device usage across different quarters.
Correlation Heatmap: A heatmap showing the correlation between different numerical features in the bookings dataset.
Example Output
After running the code, you should see the following output in the terminal:

bash
Copy code
Distinct Bookings: 5000
Distinct Sessions: 4500
Distinct Searches: 10000

Sessions with more than one booking: 300
...
You will also see several visualizations saved in the working directory as PNG files.
