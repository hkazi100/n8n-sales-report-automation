# Sales Report Automation with n8n and AI

This project automates daily sales monitoring using [n8n](https://n8n.io/) and AI-generated insights.  
It calculates daily sales drops, generates concise summaries, and sends automated email notifications to keep teams informed.  

---

## Features
- **Automated Daily Trigger**: Runs daily to track sales performance.  
- **Sales Data Parsing**: Processes CSV, API, or database input.  
- **Sales Drop Calculation**: Compares today vs. yesterday and highlights significant changes.  
- **AI Summary Generation**: Produces 2–3 sentence performance insights using AI.  
- **Email Notifications**: Sends formatted alerts automatically.  
- **Extendable Integrations**: Can be connected to Slack, Teams, dashboards, or APIs.  

---

## Workflow Overview
1. **Data Input**  
   Reads sales data either from CSV (demo) or APIs/Databases (production).  

2. **Calculation**  
   Compares current day sales with the previous day to calculate drop percentages and flag anomalies.  

3. **AI Summary Generation**  
   Generates a concise, human-readable summary explaining sales trends and potential reasons for drops.  

4. **Notification**  
   Sends email alerts with a clean format. Can be extended to Slack, Teams, or other communication platforms.  

---

## Files in this Repository
- `sales-report-workflow.json` → Exported n8n workflow for import.  
- `README.md` → Project documentation and instructions.  

---

## How to Use
1. Import `sales-report-workflow.json` into your n8n instance.  
2. Configure your data source (CSV file, API, or database).  
3. Update email credentials or notification channels to receive alerts.  
4. Schedule the workflow as needed (daily recommended).  

---

## Future Improvements
- **Direct API Integrations**: Shopify, Stripe, or SQL databases.  
- **Advanced Anomaly Detection**: Identify unusual trends automatically.  
- **Additional Notification Channels**: Slack, Teams, or custom dashboards.  
- **Customizable AI Summaries**: Allow users to define tone and depth of insights.  

---

## Tech Stack
- **n8n**: Workflow automation and scheduling.  
- **JavaScript**: Custom code for calculations and formatting.  
- **AI**: Text summarization for concise reporting.  
- **Email/Notification Services**: Gmail, SMTP, or other supported integrations.  

---

## Screenshots / Workflow Diagram
workflow-screenshot.jpeg*

---

## Author
**Habib Kazi** – Created this project to demonstrate workflow automation, AI summarization, and automated reporting capabilities.  

---

## License
This project is for **educational/demo purposes** and can be reused or modified. 
