✈️ Flight Delay Dashboard

📌 Project Overview

This project builds an interactive dashboard using Plotly and Dash to analyze flight delays across different airlines in the U.S. The dashboard enables users to input a specific year (between 2010–2020) and visualize monthly delay statistics by airline.

The goal of this project is to provide insightful visualizations for airline companies to better understand delay trends and improve operational efficiency.

📊 Dashboard Components

The dashboard contains the following visualizations (all grouped by month and reporting airline for the selected year):

Carrier Delay – Average delay caused by the airline itself.

Weather Delay – Average delay caused by weather conditions.

NAS Delay – Average delay caused by the National Airspace System.

Security Delay – Average delay due to security issues.

Late Aircraft Delay – Average delay caused by the late arrival of aircraft.

Dashboard sections are structured as:

Segment 1 → Carrier Delay + Weather Delay

Segment 2 → NAS Delay + Security Delay

Segment 3 → Late Aircraft Delay

⚙️ How It Works

User enters a year (2010–2020).

The helper function compute_info() computes the monthly average delays per airline.

Callback functions update the dashboard and generate 5 line charts using Plotly Express.

🛠️ Technologies Used

Python

Pandas – Data manipulation

Plotly Express – Interactive charts

Dash – Web application framework

🚀 How to Run the Project

Clone the repository or copy the script.

Install the required libraries:

pip install pandas dash plotly


Run the app:

python app.py


Open your browser and go to:

http://127.0.0.1:8050/

📂 Dataset

Source: Airline Dataset (CSV)

Content: Flight performance and delay statistics (2010–2020).

Encoding: ISO-8859-1

✅ Expected Output

A web dashboard with:

📌 Title of the application

📌 Input box to select a year

📌 Five line charts displayed in three segments
