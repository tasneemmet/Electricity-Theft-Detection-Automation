# Electricity Theft Detection – Automated Alert System

## Overview
An automated workflow that monitors electricity consumption risk scores and sends Telegram alerts when suspicious cases meet predefined approval conditions.

## Workflow Architecture
1. **Google Sheets:** Retrieves records with a risk score of 0.8 or higher, approved status, and no previous notification.
2. **Open-Meteo API:** Retrieves current weather information.
3. **Telegram Bot:** Sends an alert containing the customer ID, risk score, and weather context.
4. **Google Sheets:** Updates the notification status and sent timestamp.

## Technologies Used
- Make.com
- Google Sheets
- Telegram Bot API
- Open-Meteo API
- HTTP Requests

## Key Features
- Automated risk-based alert filtering.
- Approval-based notification process.
- Weather context integration.
- Telegram notifications.
- Automatic status tracking.

## Workflow Preview
![Workflow](screenshots/workflow.png)

## Important Note
A high risk score is an indicator for further investigation, not proof of electricity theft. Human review is required before taking any action.

## Project Type
Workflow Automation | API Integration | Business Process Automation
