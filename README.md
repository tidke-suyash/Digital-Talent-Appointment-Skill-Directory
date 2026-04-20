# Faculty Appointment Console 

A lightweight, browser-based directory to manage and recruit student talent. No complex backend, no database setup—just a simple spreadsheet-to-app pipeline. Made for MET Institute of Management located in Nashik. 

## The Workflow

The whole system runs on a super simple data flow:
1. **Collect Data:** Students fill out a standard Google Form with their contact details, creative interests, and academic section.
2. **Export to Excel:** You extract the Google Form responses as a `.xlsx` or `.csv` spreadsheet.
3. **Import & Go:** Upload that exact spreadsheet directly into this console. The app parses the data and instantly generates clean digital profile cards for every student.

## What It Does

* **Instant Digital Profiles:** Turns boring spreadsheet rows into interactive student cards displaying skills and experience.
* **Smart Search:** Easily filter the loaded database by specific skills, names, or hobbies. 
* **1-Click WhatsApp Hiring:** Appoint individuals for tasks directly through the platform. Clicking "Contact on WhatsApp" opens a chat with an automatic code-generated message containing the task details.
* **Local Storage:** Everything saves directly in your browser (`localStorage`). No server required.
* **Easy Backups:** Export your updated lists back into Excel at the end of the day.
* **Batch Promotion:** Built-in logic to automatically promote students to the next academic year and filter out graduating batches.

## How to Run It

Literally just open the file.

1. Download or clone `Directory.html`.
2. Double-click to open it in Chrome, Edge, Safari, etc.
3. Click **Import Dataset** to upload your exported Google Form spreadsheet.
4. You're done. Start searching and hiring!
