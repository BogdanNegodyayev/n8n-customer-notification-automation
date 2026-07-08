# Workflow Design

## Scenario

Customer request automation.

## Flow

Tally Form Submission

↓

n8n Webhook

↓

Google Sheets

↓

Telegram Notification

## Steps

1. Customer submits a request through Tally.
2. Tally sends the request data to an n8n Webhook.
3. n8n receives and processes the request data.
4. n8n saves the request data to Google Sheets.
5. n8n sends a Telegram notification to the internal team.

## Main Data Fields

- Company
- City
- Location
- Contact person
- Phone number
- Number of vehicles
- Comment
- Request status

## Status

Planned workflow. Implementation will be added later.
