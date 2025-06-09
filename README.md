# 📊 Programming Language Trends on StackOverflow
This project analyzes StackOverflow post trends over time for several programming languages using monthly data from 2008 to 2020.

## 🔄 Data Collection
- Source: StackExchange Data Explorer
- Languages Tracked: Java, Python, C, C++, C#, JavaScript, PHP, Ruby, Swift, Go, etc.
- Data can be fetched using a custom SQL query or from a provided .csv file.

## 🧪 Data Exploration
- Uses pandas to read and inspect the dataset.
- Identifies total posts per language and monthly trends.
- Highlights most/least popular languages over time (e.g., JavaScript leads overall).

## 🧼 Data Cleaning & Transformation
- Converts date strings to datetime format.
- Pivots the data for easier plotting.
- Fills missing values with zeros.

## 📈 Data Visualization
- Uses matplotlib to plot trends of language popularity.
- Compares languages side-by-side over time.
- Applies rolling averages to smooth noisy time series data.

## 📦 Libraries Used
- pandas, numpy, matplotlib, seaborn

## 📁 File Structure
QueryResults.csv: CSV with post counts per language per month.

main.ipynb: Jupyter Notebook with full analysis and visualizations.
