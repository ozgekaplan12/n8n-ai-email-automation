# n8n-ai-email-automation
# 🤖 n8n AI-Powered Email Automation

<img width="659" height="431" alt="Ekran Resmi 2025-07-10 14 27 34" src="https://github.com/user-attachments/assets/c0fd6cdd-827b-4eed-af49-d2adb8a50552" />




This project is an **AI-assisted email automation workflow** built with [n8n](https://n8n.io/).  
It reads contact data from Google Sheets, uses an AI Agent (powered by Ollama Chat Model) to generate personalized messages, and automatically sends them via Gmail.

---

## 🔧 What It Does

✅ Reads rows from a Google Sheet  
✅ Loops through each row (e.g., name, company, context)  
✅ Uses an AI Agent to generate a personalized email message  
✅ Sends the email using Gmail  
✅ (Optional) Updates the row in Google Sheets to mark the message as sent ✅

---

## 🧠 Flow Structure

1. **Manual Trigger** – Start the workflow manually  
2. **Google Sheets (Read)** – Read contact list  
3. **Loop Over Items** – Iterate over each contact  
4. **Edit Fields** – Prepare prompt inputs for the AI Agent  
5. **AI Agent (Ollama Chat Model)** – Generates a tailored email based on contact data  
6. **Gmail** – Sends the generated email  
7. **Google Sheets (Update)** – Optionally marks the contact as processed

---

## 📸 Workflow Screenshot

![AI Email Automation Flow](assets/ai-email-flow.png)

---

## 💡 Use Cases

- AI-powered cold emailing  
- Personalized marketing/outreach campaigns  
- Contact follow-ups from event or form submissions  
- Automating HR, recruitment, or B2B sales emails

---

## 🧰 Tools & Services

- `n8n`
- `Google Sheets`
- `Gmail`
- `Ollama Chat Model` (AI Agent)

---

## 📎 Notes

- You can customize the prompt for the AI Agent using the contact's name, company, and goal.  
- Make sure your Gmail account is properly authenticated via n8n OAuth2 credentials.  
- Ollama needs to be running locally or accessible via API for the chat model to work.

---


