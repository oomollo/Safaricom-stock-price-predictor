# Safaricom-stock-price-predictor
Stock Predictor
Stock Predictor is an offline web application designed to analyze and visualize historical stock data for Safaricom (SCOM) stock. This project was developed as part of an academic endeavor to explore data analysis and visualization techniques in the context of financial markets.

Project Goals
The main goals of this project are:
1.	To provide users with a clear and intuitive way to understand Safaricom's stock performance over time.
2.	To calculate and display key statistical metrics and technical indicators, such as moving averages, to aid in stock market analysis.
3.	To create an interactive and user-friendly web application that can be used by investors, analysts, and students alike.
   
Key Features
•	Historical stock data visualization
•	100-day and 200-day moving average calculations
•	Statistical analysis of stock performance metrics (high, low, open, close, volume)
•	Interactive graphs and charts for better data exploration

Technologies Used
•	Python
•	Django web framework
•	Pandas for data manipulation
•	Matplotlib for data visualization
•	HTML/CSS for web page structure and styling

Setup and Installation
Prerequisites
•	Python (version 3.9 or later)
•	Git (for version control)

Installation Steps
1.	Clone the repository: 
git clone https://github.com/oomollo/Safaricom-stock-price-predictor.git

3.	Create a virtual environment and activate it: 
python -m venv myenv
source myenv/Scripts/activate  # On Windows

4.	Install the required dependencies: 
pip install -r requirements.txt

5.	Navigate to the project directory: 
cd stock_predictor

6.	Apply the database migrations: 

python manage.py migrate
6.	Start the development server: 

python manage.py runserver
7.	Open your web browser and visit http://127.0.0.1:8000/ to access the application.
Usage
Once the application is running, you can use the following features:
1.	Historical Data Visualization: View the historical stock price data for Safaricom (SCOM).
2.	Moving Average Calculations: Observe the 100-day and 200-day moving averages to identify trends.
3.	Statistical Analysis: Explore key statistical metrics, such as the mean, standard deviation, and percentiles, for various stock performance indicators.
4.	Interactive Graphs: Interact with the charts to zoom, pan, and hover over data points for more detailed information.
