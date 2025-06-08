# 🤖 AI Agent - Gmail Notification using n8n
-
🔗 Official Website
👉 https://n8n.io
---
what is n8n to the people who don't know?
-> n8n (short for "node to node") is an open-source workflow automation tool that allows you to connect various apps and services
## 📌 Description
This n8n workflow automatically sends an email via Gmail when a chat message is received. It includes an AI agent that generates a message using the input chat and sends it through Gmail.

---
## 🔄 Workflow Flow
1. **Trigger:** When a new chat message is received.
2. **AI Agent Node:** Uses input like “I’ll be unavailable until May 29” and fills in the name and email.
3. **Gmail Node:** Sends the generated email to the appropriate recipient.
---
## 🧠 AI Prompt Example
> “Dear Team, I hope this message finds you well. I regret to inform you that I cannot attend the meeting until May 29. Thank you for your understanding.  
> Best regards, `{{ senderName }}`”
---
## 🛠️ Nodes Used
- **Chat Trigger**
- **AI Agent** (n8n AI node)
- **Gmail** (Send email using your Gmail account)
---
## 📥 Setup Instructions
1. Import the `.json` file into your n8n workspace.
2. Connect your Gmail credentials in the Gmail node.
3. Set the “To” field in Gmail to the recipient’s email address.
4. Customize AI prompt if needed.
---
## 📌 Example Use Case
- Auto-reply when unavailable.
- Smart leave notification with AI-generated message.
- Meeting auto-response bot.
