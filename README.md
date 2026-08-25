# 📞 Automated 3CX Call Center Performance Dashboard

> 🏆 **Internship Project (UIH)** End-to-End Data Pipeline & Automation

An automated data pipeline and analytics solution designed to track, manage, and visualize daily performance metrics for a 3CX Call Center. This project eliminates manual data entry by automating the extraction and organization of daily call reports, culminating in an interactive Power BI dashboard to support business decision-making.

---

## ⚙️ System Architecture & Data Pipeline
The workflow automates the entire process from receiving raw data to visualizing actionable insights.

![3CX Workflow](FLW%203CX.png)

1. **Microsoft Outlook** Automatically receives 10 daily inbound and outbound 3CX call report files via email.
2. **Microsoft Power Automate** Acts as the automation engine (Trigger & Action) to detect new emails and extract the attached report files.
3. **Microsoft SharePoint** Serves as the cloud storage solution, automatically gathering and categorizing the extracted files into designated folders.
4. **Microsoft Power BI** Connects to SharePoint, performs automated Data Cleansing, and calculates the final results to display on an Interactive Dashboard.

---

## 📊 Dashboard Overview & Features
The Power BI dashboard provides a comprehensive view of call center performance, allowing managers to monitor SLAs, track agent efficiency, and identify trends.

![3CX Dashboard Overview](dashboard%203cx.png)

**Key Performance Indicators (KPIs) Tracked**
* **Call Volume Metrics** Total Calls Received, Total Calls Answered, and Total Calls Abandoned.
* **Service Level Metrics** % Answer Rate (e.g., 98.48%) and % Abandoned Rate.
* **Time & Efficiency Metrics** Average Talk Time, Total Talking Time, and Calls Waiting > 15 seconds.

**Interactive Visualizations**
* **Trend Analysis** Line charts displaying *Abandoned Rate by Month* and *Wait > 15 by Month* to track performance stability.
* **Agent Performance** Horizontal bar chart highlighting the *Top 5 Agents (Inbound)* based on total calls answered.
* **Dynamic Filtering** Slicers for *Date (Year/Month)*, *Specific Agent*, and *Team Group* to drill down into specific data segments instantly.

---

## 🛠️ Tech Stack & Skills Highlighted
* **Automation** Microsoft Power Automate (Cloud Flows)
* **Storage & Database** Microsoft SharePoint Lists / Folders
* **Data Analytics & Visualization** Microsoft Power BI (DAX, Power Query)
* **Source Integration** Microsoft Outlook / 3CX Phone System

---

## 📁 Repository Structure
* `/data`: Contains mock datasets (e.g., `.xlsx` and `.csv` files) representing the call center data structure for safe testing.
* `/flows`: Contains the exported Power Automate workflow package (`.zip`) for reference and deployment.

---
*Designed and developed by NamthipQingxain during the AI Engineer Internship.*
