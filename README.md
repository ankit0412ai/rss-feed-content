# Automated RSS Feed Content Curation & Email Alert System 📰🤖

An automated n8n workflow designed to fetch the latest industry updates or blog posts via RSS feeds, filter relevant topics, evaluate conditions, and instantly dispatch email digests.

## 🛠️ Tech Stack & Tools
* **Workflow Automation:** n8n (Cloud)
* **Trigger Source:** Schedule Trigger (Time-based cron automation)
* **Data Source:** RSS Feed Reader
* **Data Logic:** Filter & If Nodes
* **Notification Channel:** Gmail API

---

## 🔄 How It Works (Workflow Architecture)
1. **Schedule Trigger:** Automatically runs the workflow at scheduled intervals (e.g., daily or hourly).
2. **RSS Read:** Fetches the latest articles or posts from target RSS feeds.
3. **Filter Node:** Narrows down items based on specific keywords, categories, or recency.
4. **If Condition:** Validates if the filtered content meets specific criteria before proceeding.
5. **Gmail Action:** Automatically drafts and sends targeted email alerts or newsletters.

---

## 🚀 Key Features
* **Zero Manual Tracking:** Eliminates the need to manually check blogs or news sites.
* **Smart Filtering:** Only passes high-value, keyword-matched content.
* **Automated Delivery:** Keeps stakeholders, clients, or subscribers updated in real-time.
