# Autolysis - Automated Data Analysis Tool

## What is Autolysis?
Autolysis is a simple yet powerful tool that automatically analyzes any CSV (spreadsheet) file and tells you a story about your data. Think of it as having a data analyst who can quickly look at your data and tell you what's interesting about it.

## What Does It Do?
1. **Reads Your Data**: Can handle different types of CSV files, even if they have special characters
2. **Creates Visualizations**: Automatically makes charts and graphs to help you see patterns
3. **Tells a Story**: Uses AI to explain what's interesting about your data in plain English
4. **Saves Everything**: Creates a report with charts and explanations in an easy-to-read format

## Features
- Works with any CSV file
- Creates multiple types of charts automatically
- Handles data encoding issues
- Generates easy-to-understand explanations
- Creates a complete report in markdown format

## How to Use It

1. **Setup**:
   ```bash
   # Install required packages
   pip install -r requirements.txt
   
   # Set up your AI token
   export AIPROXY_TOKEN=your_token_here
   ```

2. **Run the Analysis**:
   ```bash
   python autolysis.py your_data.csv
   ```

3. **View Results**:
   - Open `README.md` to see your analysis
   - Check the generated `.png` files for visualizations

## Example Use Cases
- Analyzing sales data
- Understanding survey responses
- Exploring scientific datasets
- Analyzing financial records
- Looking at social media metrics

## What You Get
- A written analysis of your data
- Multiple visualizations showing key patterns
- Insights about relationships in your data
- Suggestions for further analysis

## Requirements
- Python 3.8 or higher
- An AI Proxy token
- Your data in CSV format

## Note
Make sure your CSV file is properly formatted and contains valid data. The tool works best with clean, structured data but can handle various encoding issues.

---
Created by Wamiq Mushtaq
