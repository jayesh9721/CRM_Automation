# CRM Automation: Google Form → HubSpot → Slack (Make.com)

A no-code lead-capture workflow built in **Make.com**. When someone submits a Google Form, the lead is created in HubSpot, a welcome email goes out, and the sales team gets an instant Slack alert. Nobody has to copy data by hand, and response time drops from hours to seconds.

## Workflow
```
Google Form ─▶ Google Sheets (Watch Rows) ─▶ Send welcome email
                                          ─▶ HubSpot: create contact
                                          ─▶ Slack: notify sales channel
```

| Step | Make module | What it does |
|---|---|---|
| 1 | Google Sheets – Watch Rows | Triggers on every new form response |
| 2 | Email – Send an Email | Sends the lead a welcome email |
| 3 | HubSpot CRM – Create Contact | Adds the lead to the CRM |
| 4 | Slack – Create Message | Posts the new lead to the team channel |

## Use it
1. In Make.com, create a new scenario → **⋯ → Import Blueprint** → choose [`make-scenario-blueprint.json`](make-scenario-blueprint.json).
2. Reconnect your own Google Sheets, email, HubSpot and Slack connections.
3. Point the Sheets module at your form's response sheet, then set the Slack channel and email recipient.
4. Turn the scenario on.

## Tools
Make.com · Google Forms · Google Sheets · HubSpot CRM · Slack

## License
MIT, see [LICENSE](LICENSE).
