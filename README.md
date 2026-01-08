# 🤖 AI-Powered Trending Topic Research Automation (n8n)

## 📌 Overview
This project automates the process of researching trending topics across multiple digital platforms and generates actionable content ideas using AI. It is designed for marketing teams and agencies to reduce manual research time and improve content ideation efficiency.

The automation is built using **n8n**, integrates multiple external APIs, applies AI-driven analysis, and stores structured insights in **Google Sheets**.

---

## 🚀 Key Features
- ⏰ Fully automated scheduled execution
- 🎯 Dynamic keyword selection strategy
- 📺 YouTube trending video analysis
- 📰 News trend aggregation using NewsAPI
- 🤖 AI-powered content ideation logic
- 📊 Persistent storage in Google Sheets
- 🛡️ Production-ready error handling with graceful degradation

---

## 🛠️ Tech Stack
- **Workflow Automation**: n8n
- **APIs**:  
  - YouTube Data API v3  
  - NewsAPI  
  - OpenAI (Chat-based LLM logic)
- **AI Model**: ChatGPT (GPT-3.5 logic)
- **Storage**: Google Sheets

---

## 🧠 Workflow Architecture
1. Scheduled trigger executes workflow automatically
2. Random marketing keyword selected from predefined list
3. Trending data collected from multiple platforms
4. Data merged into unified structure
5. AI logic analyzes trends and generates content ideas
6. Insights stored in Google Sheets
7. Workflow continues gracefully if any external API fails

---

## 📂 Output Format (Google Sheets)
| Timestamp | Keyword | Source | Title | Description | Relevance |
|---------|--------|--------|-------|-------------|-----------|

---

## ⚙️ Setup Instructions
1. Import the provided n8n workflow JSON
2. Configure API credentials:
   - YouTube Data API
   - NewsAPI
   - OpenAI API
3. Connect Google Sheets
4. Activate the workflow schedule

---

## ⚠️ Notes & Limitations
- Twitter/X API access is limited on free tiers and is documented as a limitation
- OpenAI execution frequency may be restricted on free plans
- Mock AI output is included to demonstrate downstream workflow functionality under quota constraints

---

## 🔮 Future Enhancements
- Slack / Email notifications
- Sentiment and engagement scoring
- Database storage (PostgreSQL / Airtable)
- Multi-language trend analysis
- CRM and marketing tool integrations

---

## 👤 Author
**Shivam Raval**  
AI & Automation Enthusiast  

---

## 📄 License
This project is created for educational and assessment purposes.
