# AI-Powered Daily Motivational Email Automation

An n8n workflow that uses an AI model to generate a motivational quote and automatically emails it to a recipient list every day at **7:00 AM Africa/Lagos time**.

## Workflow

`Schedule Trigger → Message a Model → Google Sheets → Gmail`

1. **Schedule Trigger** starts the workflow on its daily schedule.
2. **Message a Model** generates a motivational quote.
3. **Google Sheets** supplies the recipient information.
4. **Gmail** sends the email.

## Tools

- n8n
- AI model integration
- Google Sheets
- Gmail
- Scheduled workflow automation

## Business Use Case

This project demonstrates how recurring communication can run with less manual effort. The same pattern can be adapted for reminders, internal updates, customer follow-ups, and other routine business messages.

## Project Evidence

- [ ] Sanitized n8n workflow JSON
- [ ] Workflow screenshot
- [ ] Successful email delivery screenshot
- [x] [Loom walkthrough video](https://www.loom.com/share/3698b08fe74a4a9e8da4990402397cb4)

Screenshots and a sanitized workflow export will be added when ready.

## Security

This repository does not include credentials, API keys, private recipient email addresses.
## Status

Tested successfully with email delivery confirmed. This is a learning and portfolio project.
