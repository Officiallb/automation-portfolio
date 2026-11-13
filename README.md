# Automation Portfolio

Automation workflows I have built and documented. Each project folder contains the exportable workflow, a plain-language explanation of what it does, setup steps, and screenshots of it running.

All example data in this repo (names, emails, companies) is fake. No credentials or private IDs are included.

## Projects

| # | Project | What it does | Tools |
|---|---------|--------------|-------|
| 01 | [Lead Capture and Auto-Reply](./01-lead-capture-auto-reply) | Takes a new lead from a form, checks whether they have contacted you before, sends them an AI-written confirmation email, alerts the team in Slack, and logs the lead in a Google Sheet. | n8n, Google Sheets, Gemini, Gmail, Slack |
| 02 | [AI Recruitment Screening](./02-ai-recruitment-screening) | Screens job applications automatically: validates the form data, flags duplicates, reads the resume PDF, scores the candidate against the role's requirements, logs everything in a Google Sheet and alerts the team. A second flow drafts shortlist and rejection emails and books interviews on Google Calendar. | n8n, Google Sheets, Gemini, Gmail, Slack, Google Calendar |
| 03 | [Invoice and Payment Automation](./03-invoice-payment-automation) | Turns a form request into a Stripe payment link and an emailed invoice, then verifies the payment when the client pays, marks the invoice paid in a Google Sheet, alerts the team and emails a receipt. A daily check drafts reminders for overdue invoices. | n8n, Stripe, Google Sheets, Gmail, Slack |

More projects will be added as separate numbered folders.

## How to use a project

1. Open the project folder and read its README.
2. Import `workflow.json` into your automation tool.
3. Connect your own accounts and replace the placeholder IDs.
4. Send the sample payload to test it.

## Contact

Onakoya Favour: [GitHub](https://github.com/Officiallb)
