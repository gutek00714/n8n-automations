# n8n Automations

This repository contains my custom automations created in [n8n](https://n8n.io/).  
Each workflow demonstrates how to integrate APIs, manage data, and automate repetitive tasks.

---

## 📄 CV.json — Job Application Tracker

**Goal:** Automatically track job application statuses via email.

**How it works:**
1. Once a day, checks Gmail for emails containing specific keywords.  
2. Scans the content for rejection phrases.  
3. Extracts the company name from the sender’s email domain (`@company.com`).  
4. Sends the name to ChatGPT for comparison with entries in a Google Sheets file.  
5. Updates the spreadsheet row with “Rejected” or “Invite to interview.”

**Technologies used:**  
- n8n  
- Gmail API  
- Google Sheets API  
- OpenAI ChatGPT API  

<img width="2492" height="395" alt="obraz" src="https://github.com/user-attachments/assets/16e490d4-8f43-4f1d-988a-979eeb05720f" />
---

## 🎲 BoardGame.json — Contest Alert Bot

**Goal:** Notify me on Discord whenever a new board game contest is published.

**How it works:**
1. Once a day, makes an API call to retrieve the latest contests.  
2. Compares results with a Google Sheets record.  
3. If a new contest appears, sends a message to a Discord channel via webhook.

**Technologies used:**  
- n8n  
- Discord Webhook  
- REST API calls  
- Google Sheets API  

<img width="1882" height="523" alt="obraz" src="https://github.com/user-attachments/assets/637d2e7a-192d-49f8-b1ee-ade79ea842af" />
