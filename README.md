# Automated Feedback Analysis Workflow

## Business Problem
In many organizations, customer feedback collected through forms is a rich source of insight, but the process of manually reading, interpreting, and logging this feedback is time-consuming and inefficient. This manual process leads to delays in identifying customer sentiment, prevents rapid response to negative experiences, and makes it difficult to analyze trends over time without significant effort.

## Solution Overview
This project solves the problem by creating a fully automated, end-to-end system that captures, analyzes, and routes customer feedback in real-time. The workflow instantly triggers when a customer submits a Google Form. It then uses Google's Gemini AI to perform sentiment analysis and generate a concise summary of the feedback. Finally, it stores this structured data in a Google Sheet and sends an immediate email alert to the customer success team if the feedback is negative, enabling proactive intervention.

## Tools Used
* **Make.com:** The core automation platform used to orchestrate the workflow.
* **Google Forms:** The front-end for capturing customer feedback.
* **Google Gemini AI:** The AI engine for sentiment analysis and text summarization.
* **Google Sheets:** The database for storing original feedback and AI-generated insights.
* **Gmail:** The tool for sending automated alerts for negative feedback.

## Workflow Diagram

<!-- 
********************************************************************************
<img width="953" height="504" alt="image" src="https://github.com/user-attachments/assets/1c5446df-b29f-485c-9eb6-fcca34631b4d" />

********************************************************************************
-->
![Workflow Diagram for Feedback Analysis][(https://github.com/user-attachments/assets/1c5446df-b29f-485c-9eb6-fcca34631b4d)]

## Key Features & Results
-   **End-to-End Automation:** Orchestrated a multi-step workflow in Make.com to instantly capture Google Forms submissions and process them without manual intervention.
-   **AI-Powered Insights:** Integrated Google's Gemini AI to perform sentiment analysis and generate concise summaries, transforming unstructured feedback into actionable data.
-   **Proactive Alerting:** Engineered a conditional routing system that automatically sends email alerts via Gmail for negative feedback, allowing for rapid response to at-risk customers.

## Business Value
This automation transforms a manual, reactive process into a real-time intelligence system.
-   **Eliminates Manual Work:** Frees up significant time for the Customer Success team.
-   **Enables Proactive Service:** Allows the team to address issues before they escalate, improving customer retention.
-   **Creates a Structured Data Asset:** Builds a clean, organized dataset in Google Sheets, perfect for long-term trend analysis.
