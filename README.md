# 📧 AI Gmail Auto Reply Agent (n8n + Gemini)

This project is an **AI-powered email automation workflow** built using **n8n**, **Google Gemini AI**, and **Gmail API**.  
It automatically reads incoming emails, understands context, and sends smart, professional replies.

---

## 🚀 Features

- 📩 Automatically triggers on new Gmail emails
- 🧠 Uses Google Gemini AI to understand email intent
- ✍️ Generates human-like professional replies
- 📤 Sends responses directly via Gmail
- 🔄 Supports different email types:
  - Business inquiries
  - Complaints
  - Meeting requests
  - Questions
  - Casual conversations
- 🗣️ Matches sender tone & language
- ⚡ Fully automated workflow (no manual effort)

---

## 🧠 Tech Stack

- n8n (Automation workflow)
- Google Gemini (AI model)
- Gmail API (Email sending/receiving)

---

## ⚙️ How It Works

1. Gmail Trigger detects new email
2. AI Agent reads subject + content
3. Gemini AI analyzes intent
4. AI generates professional reply
5. Gmail Tool sends response automatically

---

## 📁 Workflow File

- `workflow.json` → Import directly into n8n

---

## 🔐 Security Note

- Replace credentials before deployment
- Never expose Gmail OAuth keys in public repositories
- Never expose Google Gemini API keys
- Never upload access tokens or client secrets

---

## 📸 Screenshots

### 🔄 n8n Workflow

[n8n Workflow](screenshots/workflow.jpg)

### 📩 Mail & Reply

[Mail & Reply](screenshots/email&reply.jpg)

---

## 📌 Use Cases

- Email automation for freelancers
- Customer support auto replies
- Business inbox management
- AI assistant integration

---

## ⚠️ Limitations

- Requires Gmail API access
- Requires Google Gemini credentials
- Requires an active n8n workflow
- AI-generated responses may require human review
- API limitations may apply

---

## ⭐ Future Improvements

- Spam filtering
- Multi-language support
- Human approval mode
- CRM integration
- Email priority classification
- Custom reply templates
- Email analytics
- Calendar integration

---

## 👨‍💻 Author

Made by Irshad Ali  
B.Tech CSE (AI & ML) | Web Dev & AI Automation Learner

GitHub: https://github.com/Irshadali1786

---

## 📌 License

MIT License
