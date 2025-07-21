# Teams Chat Content Moderation Service – CST8917 Lab 3

## Student Info
**Name:** Keval Trivedi  
**Course:** CST8917  
**Lab:** 3 – Teams Chat Moderation  
**Date:** July 20, 2025

---

## Objective

This Logic App monitors Microsoft Teams chat messages for inappropriate content. When a message containing specific keywords is detected, the app sends an email alert to an administrator.

---

## Technologies Used

- **Azure Logic Apps**
- **Microsoft Teams Connector**
- **Office 365 Email (Outlook)**

---

## Logic App Workflow

1. **Trigger:** Runs when a new Teams message is posted in a selected channel
2. **Condition:** Checks if the message contains a specific keyword (e.g., `badword`)
3. **Action:** If matched, sends an email notification to the admin with message content and sender info

---

## Email Notification

The email contains:
- Message content
- Sender’s name
- Timestamp
- Conversation ID

---

## Testing

- Sent a message with the word "badword" in Teams → **email alert was triggered**
- Sent a normal message → **no email sent**
- Verified the Logic App runs and works as expected

---

## Challenges Faced

- Setting up Teams trigger took time due to permissions
- Exploring trigger body to get sender name and conversation ID was tricky
- Slight delay (20–30 seconds) in receiving email during testing

---

## Future Improvements

- Use Cognitive Services for advanced content detection (hate speech, threats)
- Add more flexible word detection using a list or regex
- Store flagged messages in a database or SharePoint for future review

---

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 10 24 PM" src="https://github.com/user-attachments/assets/e70663c3-d28a-4663-8f89-de4ccf45e21f" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 13 10 PM" src="https://github.com/user-attachments/assets/71172bb6-5398-43bd-b582-a6b15464c7f9" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 11 37 PM" src="https://github.com/user-attachments/assets/0f9a3690-8c27-4ee2-a043-943db024e86d" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 11 04 PM" src="https://github.com/user-attachments/assets/235b0f61-cb87-481e-a7cc-c89bdc902c0a" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 12 49 PM" src="https://github.com/user-attachments/assets/88c147df-1cb7-4c58-b091-f662832fa792" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 11 44 PM" src="https://github.com/user-attachments/assets/b3bde0b7-2a0e-4a07-b498-c0ece7c9e2f4" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 12 07 PM" src="https://github.com/user-attachments/assets/686d12c7-fdf5-405f-9a82-b6dfdcef7cfe" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 11 55 PM" src="https://github.com/user-attachments/assets/539ce19b-3b8f-4296-b521-6aa29754d980" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 11 29 PM" src="https://github.com/user-attachments/assets/43d94efd-4f5f-4d87-8f26-c9b97c98ecfc" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 12 32 PM" src="https://github.com/user-attachments/assets/5bded476-f58e-4162-a03a-f0ff9e78dd53" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 11 18 PM" src="https://github.com/user-attachments/assets/a320803d-9e1e-4509-9eb1-d5abe6f9de02" />

<img width="1470" height="956" alt="Screenshot 2025-07-20 at 8 12 24 PM" src="https://github.com/user-attachments/assets/b3fe6187-067d-48fd-a9af-ebe359d97156" />


