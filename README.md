# 📅 Smart Calendar Assistant

A lightweight, privacy-focused Chrome extension (Manifest V3) designed to help users intelligently extract event details from active webpages and sync them directly to Google Calendar with a single click.

---

## ✨ Features

- **🧠 AI-Powered Extraction**: Intelligently parses webpage text and metadata to detect event titles, dates, times, and locations.
- **⚡ One-Click Sync**: Directly adds extracted events to your primary Google Calendar via Google OAuth 2.0 API.
- **🔒 Privacy First**: Operates locally on your browser. No personal data or webpage content is stored or collected on external servers.
- **⚙️ Customizable Settings**: Allows users to configure their own custom API keys and preferences locally.

---

## 🛠️ Tech Stack

- **Extension Architecture**: Chrome Extensions Manifest V3 (JavaScript, HTML, CSS)
- **APIs & Protocols**: 
  - Chrome Extensions APIs (`activeTab`, `scripting`, `identity`, `storage`)
  - Google Calendar API & OAuth 2.0
- **UI**: Clean, minimalist popup interface

1. add the api and model <br>
<img width="461" height="136" alt="image" src="https://github.com/user-attachments/assets/5919ff17-49f8-4ef7-9ba1-4126c1270b59" /> <br>

2. extract and summarize the information<br>
<img width="461" height="374" alt="image" src="https://github.com/user-attachments/assets/17e726ec-5df3-4d10-812e-a9e5bc309721" /> <br>

3. confirm the details and add to the google calendar<br>
<img width="479" height="668" alt="image" src="https://github.com/user-attachments/assets/9776d56a-147d-4c84-abd3-dbcb6bd21555" /><br>



---

## 📦 Installation & Local Setup

If you want to run this extension locally, you can down the crx file in this folder
