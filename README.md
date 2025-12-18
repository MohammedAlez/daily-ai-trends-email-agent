# Daily AI Trends Email Agent (n8n)

An AI-powered automation that sends a **daily email** summarizing the **latest AI trends and news** every morning.

## 🚀 What it does
- Runs automatically every morning
- Fetches recent AI-related topics
- Uses an AI model to summarize trends
- Sends a clean, readable email to the user

## 🧠 Tech Stack
- n8n
- Gemini 
- Cron Trigger
- Email (Gmail)

## 🔄 Workflow Overview
1. Cron trigger runs every morning
2. AI generates a summary of current AI trends
3. Email is sent to the configured address

## 📦 How to use
1. Import `workflow.json` into n8n
2. Set credentials:
   - OpenAI API key
   - Email (SMTP or Gmail)
3. Adjust the email recipient
4. Activate the workflow
