# Automated Real Estate Data Scraping & Economic Analysis

## 📌 Project Overview
This project automates the extraction of real estate listings from supported websites and generates an **economic report** based on predefined financial metrics. The financial report includes revenue projections, cost breakdowns, and profit calculations for properties meeting specific criteria.

## ⚙️ Features
- **Web Scraping:** Collects real estate listings from websites without CAPTCHA.
- **Automated Economic Model:** Generates financial reports for properties larger than 200m².
- **Excel Report Generation:** Creates separate sheets per property with dynamic formulas.
- **User-Defined Profit Calculation:** Allows the user to modify input values and auto-update the financial analysis.

## ⚙️ Configuration
The script scrapes all real estate listings from the website.
For properties larger than 200m², it calculates the division into four smaller apartments.
The resale price per unit is set to €350,000 (modifiable in the script).
It automatically calculates the Profit/Loss of scouting based on acquisition costs, renovation costs, and projected revenue.
All financial calculations and related formulas are dynamically updated in the Excel report.

## 🔄 Future Improvements
Expand data sources: Integrate more property listing websites.
Image Processing: Planimetry analysis via Convolutional Neural Networks (CNN).
Web Interface: Create a simple UI for data input & visualization.

## 🛠️ Installation
Ensure you have Python 3.8+ installed on your system.

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/real-estate-analysis.git
   cd real-estate-analysis
