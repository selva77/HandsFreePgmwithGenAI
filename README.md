# HandsFree Pgm with GenAI

**Automation of End to End Status Reporting Workflow**

This repository contains Google Workspace Scripts designed to automate and enhance the creation, distribution, and archival of weekly status reports.

**Key Features
**

**threeSendWsrReminderEmailsFileGenAI()
**
Sends automated email reminders to contributors to update their status in the report.
Employs an AI model (through Google's Generative Language API) to summarize the most important updates, providing a concise snapshot of progress.
Simplifies the process and increases engagement in status updates.
**sendWsrEmail()
**
Automatically extracts key updates from the status report using an AI model (through Google's Generative Language API).
Creates a draft email summarizing the impactful updates.
Streamlines reporting for efficiency and focus.
**wsrCopyAndRename()
**
Archives previous versions of the weekly status report, ensuring historical records.
Maintains orderliness and accessibility.
**How to Use
**
Set up your Google Workspace environment:
Create a folder in Google Drive to store your weekly status reports. Note the folder ID.
Update the folderId, archiveFolderId, and myApiKey variables in the code with the respective values.
Create a Google Doc or Google Slides to serve as your status report template.
Schedule the scripts to run automatically:
Go to Tools -> Script Editor in your Google Spreadsheet.
Under Triggers, set up the scripts to run on a schedule that aligns with your reporting workflow.
Contact
For questions, support, or to suggest enhancements, please reach out to [your email or a designated support channel].
