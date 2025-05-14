
  <h1>🤖 CRM Automation – Google Form → HubSpot → Slack (via Make.com)</h1>

  <h2>📜 Project Overview</h2>
  <p>
    This project showcases a no-code CRM automation workflow using <strong>Make.com</strong>. When a user submits a <strong>Google Form</strong>, the lead data is automatically pushed to <strong>HubSpot CRM</strong> and an instant alert is sent to the relevant team on <strong>Slack</strong>. The goal is to improve lead management and response time without writing custom code.
  </p>

  <h2>✨ Features</h2>
  <ul>
    <li>📥 Collect leads via Google Forms</li>
    <li>🔗 Automatically create/update contacts in HubSpot</li>
    <li>🔔 Instantly notify team members on Slack</li>
    <li>✅ No manual data entry required</li>
    <li>📊 Centralized lead tracking and alerts</li>
  </ul>

  <h2>🛠️ Tools & Services Used</h2>
  <ul>
    <li>📄 Google Forms – For capturing lead information</li>
    <li>📊 Google Sheets – Stores form responses</li>
    <li>⚙️ Make.com – For automation/integration</li>
    <li>🧩 HubSpot – CRM where leads are stored</li>
    <li>💬 Slack – Notification delivery to team channels</li>
  </ul>

  <h2>🚀 Workflow on Make.com</h2>
  <ol>
    <li>Trigger: New row added in Google Sheet from Form submission</li>
    <li>Action: Create or update a contact in HubSpot</li>
    <li>Action: Send formatted notification message to a Slack channel</li>
  </ol>

  <h2>📁 Structure</h2>
  <pre>
make-crm-automation/
├── Google Form (linked to Google Sheet)
├── Make Scenario:
│   ├── Google Sheets Watch Rows
│   ├── HubSpot Create/Update Contact
│   └── Slack Send Message
├── README.html
  </pre>

  <h2>🔐 Notes</h2>
  <p>
    Make.com handles authentication securely via connected services. All scenarios are set to run automatically on new form entries, reducing delays in response.
  </p>
