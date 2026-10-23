# AI-Powered Daily Motivational Email Automation

An n8n workflow that uses an AI model, Google Sheets, and Gmail to generate and send daily motivational emails automatically at **7:00 AM Africa/Lagos time**.

## Demo

- **[Watch the Loom walkthrough](https://www.loom.com/share/3698b08fe74a4a9e8da4990402397cb4)**

## How It Works

`Schedule Trigger → Message a Model → Google Sheets → Gmail`

1. **Schedule Trigger** starts the workflow each morning.
2. **Message a Model** generates the motivational content.
3. **Google Sheets** provides the recipient data.
4. **Gmail** sends the email automatically.

## Tools Used

- n8n — workflow automation
- AI model integration — content generation
- Google Sheets — recipient data source
- Gmail — email delivery

## What This Project Demonstrates

- Scheduling an automated workflow
- Generating content with an AI model
- Connecting multiple services in one workflow
- Using spreadsheet data in an automated process
- Sending emails automatically through Gmail

## Business Applications

The same workflow pattern can be adapted for recurring reminders, internal updates, customer follow-ups, lead nurturing, and other routine business communications.

## Validation

The workflow was tested, and successful email delivery was confirmed.

## Project Assets

- [x] Loom walkthrough video
- [ ] Workflow screenshots
- [ ] Successful email delivery screenshot
- [ ] Sanitized n8n workflow export

The screenshots and workflow export should be linked here once their public repository paths are available.

## Security

Do not publish API keys, credentials, private recipient email addresses, or a link to the live recipient spreadsheet. Before sharing an n8n workflow export, remove credentials and other sensitive configuration.

## Status

Completed and tested as a learning and portfolio project.
