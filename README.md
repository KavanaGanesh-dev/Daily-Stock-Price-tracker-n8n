# Daily-Stock-Price-tracker-n8n
Automate daily stock price tracking using n8n, Python and Gmail. This workflow fetches real-time data for 10 stocks via RapidAPI, format it with a Python node , and emails a daily summary automatically

**This project automates daily stock market updates using n8n, Python and Gmail**

**Overview**
Everyday the workflow automatically does the following steps:
1. Triggers at a specific time using Triggering Schedule
2. Fetches the real-time stock prices for 10 companies from Yahoo Finance API via the RapidAPI
3. Process and formats the data with a Python Code
4. Sends a clean, readable stock summary email through Gmail


**Tech Stack Used**
1. n8n - Workflow Automation Platform
2. Python (n8n code node) - Data Processing and Formatting
3. Rapid API (Yahoo Finance API) - Real Time stock data
4. Gmail Node - Email Authentication


**Workflow Structure**
1. Schedule Trigger - runs daily
2. HTTP Request -  calls the API stock
3. Python Code - formats the JSON into readable text
4. Gmail Node - send summary email 


**API Setup**
1. Create an account on RapidAPI
2. Subscribe to Yahoo Finance
3. In the HTTP Request Node copy the X-RapidAPI-Key and X-RapidAPI-Host



