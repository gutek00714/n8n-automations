# n8n-automations
CV.json automation:
<img width="2492" height="395" alt="obraz" src="https://github.com/user-attachments/assets/16e490d4-8f43-4f1d-988a-979eeb05720f" />

I created this automation to keep track of my job applications. Once a day, it checks my Gmail for emails containing specific keywords. It then scans the email content for rejection phrases. If a rejection is detected, it extracts the company name from the sender’s email address (the part after the “@”) and sends it to ChatGPT to compare with the company names in my Google Sheets file. Finally, it updates the corresponding row in the spreadsheet with either “rejected” or “invite to interview,” depending on the email content.

BoardGame.json
<img width="1882" height="523" alt="obraz" src="https://github.com/user-attachments/assets/637d2e7a-192d-49f8-b1ee-ade79ea842af" />

I created this automation to receive a Discord notification whenever a new contest is published. Once a day, it makes an API call to retrieve the latest contests and compares them to the list in my Google Sheets file. If a new contest is found, it sends a notification to Discord via a webhook.
