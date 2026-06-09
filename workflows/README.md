# n8n Workflow Exports

This directory contains ready-to-import n8n workflow JSON files.

## How to Import

1. Open your n8n instance
2. Go to **Workflows** > **Import from File**
3. Select the .json file from this directory
4. Configure the credentials and environment variables
5. Test in sandbox mode before going live

## Available Workflows

- **lead-capture-router/** — Routes inbound leads from web forms to CRM and triggers follow-up sequences
- **appointment-booker/** — Connects booking forms to calendar and sends confirmations
- **missed-call-recovery/** — Detects missed calls and triggers SMS/email follow-up
- **review-request/** — Sends review requests after service completion
- **voicemail-drops/** — Automated voicemail drop campaigns for outbound sales

> Add your workflow JSON files here. Each workflow should include a brief README describing what it does and what credentials it needs.
