
# Sales Dashboard
This Streamlit app displays a Sales Dashboard based on an Excel file containing sales data. The user can filter the data by selecting a city, customer type, and gender.

## Setup
The following Python packages need to be installed:

pandas (can be installed via pip install pandas openpyxl)
plotly-express (can be installed via pip install plotly-express)
streamlit (can be installed via pip install streamlit)
![image](https://github.com/mipranjal/Interactive-Sales-Dashboard/assets/110101325/65bd5d98-7f36-4098-ab32-6f6df7bbebaa)

## How to Run
To run the app, execute the following command in the terminal:
code: streamlit run <filename>.py
where <filename>.py is the name of the Python file containing the code.

## App Layout
The app layout consists of a sidebar on the left-hand side and a main page on the right-hand side.

The sidebar contains filters to select the data based on the city, customer type, and gender.

The main page displays two charts:

Sales by Product Line (bar chart)
Sales by Hour (bar chart)
Data Source
The app reads the data from an Excel file located in the interactive-dashboard directory, named supermarkt_sales.xlsx.

## Additional Information
The app uses emojis from https://www.webfx.com/tools/emoji-cheat-sheet/.

The app hides Streamlit's default style for a cleaner look.
