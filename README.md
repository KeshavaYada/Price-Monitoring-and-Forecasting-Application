# 📈 Price Monitoring and Forecasting Application

🎉 Welcome to the **Price Monitoring and Forecasting Application** repository! This project is built on the Microsoft Power Platform, offering supply chain professionals advanced insights and analytical tools for efficient price monitoring and forecasting. Sensitive information has been omitted or redacted for confidentiality.

---

## 📋 Project Overview

💼 **Objective**: This application provides real-time price tracking, forecasting capabilities, and sensitivity analysis to enhance decision-making in supply chain management.

🔍 **Core Functionality**: By integrating real-time data monitoring and predictive analytics, this application supports supply chain professionals in visualizing price trends, assessing delivery metrics, and analyzing profit/loss, all from a single platform.

---

## 🖥️ Application Features

Here’s a breakdown of the core features of the Price Monitoring and Forecasting Application:

- **📊 Real-time Price Tracking**: Continuously monitors price variations, subcontracted amounts, commodity prices, and delivery schedules, providing instant insights.
  
- **📈 Forecasting and Predictive Analysis**: Uses advanced forecasting techniques, including **moving averages** and custom percentages, to predict future price trends and perform **what-if analysis**.

- **💡 Price Sensitivity Analysis**: Analyzes the impact of changes in commodity prices on total costs and profitability.

- **🚚 Delivery Analysis**: Tracks and compares actual vs. planned delivery quantities over time.

- **📉 Profit/Loss Tracking**: Provides clear visibility into profit and loss metrics using interactive charts and visualizations.

- **🔔 Alert Mechanisms**: Sets alerts for stakeholders when significant price deviations or potential risks are detected.

---

## 🧰 Tech Stack

Here’s an overview of the tools and technologies powering this application:

- **Power BI**: For data visualization and interactive dashboards.
- **Power Apps**: Custom UI and visual components for user interaction.
- **Power Automate**: Automates workflows and data refreshes.
- **Azure SQL Database**: Central repository for price data storage and querying.
- **Azure Data Factory**: ETL (Extract, Transform, Load) processes for data integration from multiple sources.
- **SharePoint**: Stores user inputs and interactions from Power Apps visuals.

---

## 🛠️ Application Architecture

The application follows a streamlined data flow within the Microsoft ecosystem:

1. **Data Extraction**: Data from various sources is extracted using **Azure Data Factory** and loaded into the **Azure SQL Database**.
2. **Dashboard Connectivity**: Power BI dashboards connect to the Azure SQL Database through **Direct Query** for real-time updates.
3. **Interactive Visuals**: Power Apps visuals embedded in Power BI dashboards enable users to interact with the application directly.
4. **User Data Storage**: Inputs from Power Apps visuals are stored in **SharePoint**.
5. **Automated Updates**: Power Automate triggers updates to the Azure SQL Database based on user inputs.
6. **Real-time Refresh**: The updated database refreshes Power BI dashboards, providing the latest insights.

---

## 🎯 Impact

The Price Monitoring and Forecasting Application has achieved a **30% cost reduction** by consolidating multiple tools into an integrated platform. Features like predictive what-if analysis, profit/loss visualization, and real-time alerts have driven significant cost savings, improved decision-making, and enhanced negotiation power in tender pricing discussions.

---

## 📁 Repository Structure

- **`README.md`**: Overview and documentation of the project (you’re reading it!)
- **`visualizations/`**: Includes screenshots or sample visuals from the application.

---


