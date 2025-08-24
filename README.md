# Instant-Gmail-Notifications-for-Google-Form-Submissions
Get a single Gmail notification immediately whenever someone submits your Google Forms. The workflow watches the Form-linked Google Sheets for new rows and sends a clean, readable email within about a minute—perfect for time-sensitive workflows.

## Context
Stay responsive to urgent requests without inbox overload. Get notified immediately when new submissions arrive, with all key details in one clean email.

## Who is this for?
- Teams collecting support requests, project inputs, or approvals.

- Anyone who needs to respond quickly to new form submissions.

- Perfect for time-sensitive workflows.

## Requirements
- Google account

- A Google Forms linked to a Google Sheets (Responses → “Link to Sheet”)

- Gmail account connected to n8n (OAuth)

## Steps

<img width="1206" height="471" alt="image" src="https://github.com/user-attachments/assets/92150379-a798-4917-a11a-50bcaad09b7c" />


🗒️ Use the sticky notes in the n8n canvas to:

- Create a Google Forms and link it to a Google Sheets.

- Credentials: Add/verify Google (Sheets) and Gmail credentials in n8n.

- Add Google Sheets Trigger node.

- Spreadsheet: your Form-linked sheet.

- Polling interval: every 1 minute (or adjust as needed).

- Send Gmail: Add Gmail node and set up recipient team inbox or on-call email.

- Test & Activate: Submit a sample form, wait 1 minute, confirm the email.

- Make sure the workflow is always activated.

You’ll get this:
<img width="936" height="391" alt="image" src="https://github.com/user-attachments/assets/4771c3d8-d032-4182-a35c-e428ea9370e7" />

A Gmail message with key details (requester, summary, priority, link to the sheet), easy to scan and act on.

## Tutorial video
https://www.youtube.com/watch?v=kO7GdPOJMus

## How it works
⏰ Trigger: workflow runs every time you get a request from the form (trigger checks every minute)

📝 Prepare: Format the submission into a concise message.

📨 Notify: Sends one Gmail email per submission

## Link
Get the free template here https://n8n.io/workflows/7432-instant-gmail-notifications-for-google-form-submissions/


