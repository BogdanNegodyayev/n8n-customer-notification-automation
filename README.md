# n8n Customer Notification Automation

Workflow automation project for processing customer requests and sending automated notifications using n8n, REST APIs, Telegram Bot API, Google Sheets, and WhatsApp automation.

## Project Goal

The goal of this project is to automate manual customer request processing and reduce routine operational work.

This automation is designed for companies that receive customer requests, store data in Google Sheets or CRM systems, and need automatic notifications for internal teams or customers.

## What this project automates

- Customer request processing
- Internal team notifications
- Telegram notifications
- WhatsApp notifications via Green API
- Google Sheets updates
- API-based workflow logic

## Tech Stack

- n8n
- REST APIs
- Webhooks
- JSON
- Google Sheets
- Telegram Bot API
- Green API
- CRM workflows

## Workflow Logic

1. A new customer request is received.
2. The request data is saved or updated in Google Sheets.
3. n8n processes the request data.
4. The workflow sends an internal Telegram notification.
5. If required, the workflow sends a WhatsApp notification.
6. The request status can be updated automatically.

## Business Value

This automation helps reduce manual work, improve response speed, and make customer request handling more consistent.

## Status

This project is based on real business automation experience.  
A public demo workflow will be added later after removing sensitive business data.

## Author

Bogdan Negodyayev  
Technical Support & Implementation Specialist  
Astana, Kazakhstan
