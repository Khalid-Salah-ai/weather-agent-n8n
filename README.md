# Weather Agent — n8n Automation

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![n8n](https://img.shields.io/badge/Built%20with-n8n-red)
![Last Commit](https://img.shields.io/github/last-commit/Khalid-Salah-ai/weather-agent-n8n)

My first AI automation project using n8n.  
This workflow fetches real-time weather data and generates a natural-language weather report using an AI agent.

## 📸 Workflow Screenshot

![Workflow Screenshot](https://github.com/Khalid-Salah-ai/weather-agent-n8n/blob/main/Screenshot%202026-04-25%20215545.png)

---

## 🌤️ Features

- Fetches real-time weather data automatically  
- Sends a daily email with a clear weather summary  
- Uses OpenWeatherMap API + Gmail OAuth2  
- Fully customizable workflow  
- Easy to export, import, and extend  

---

## 📦 Repository Structure


---

## 🚀 How It Works

1. A Schedule Trigger runs every morning.  
2. The workflow calls OpenWeatherMap API to fetch weather data.  
3. n8n formats the data into a readable weather report.  
4. Gmail node sends the report to the configured email address.  

---

## 🛠️ Prerequisites

- Running n8n instance (local, cloud, or self-hosted)  
- OpenWeatherMap API key  
- Gmail OAuth2 credentials  
- Basic familiarity with n8n editor  

---

## ▶️ Running the Workflow

- Open the workflow in n8n  
- Click **Execute Workflow**  
- Verify weather data + email delivery  
- Once confirmed, the schedule trigger handles daily automation  

---

## 🔧 Modifying the Workflow

- Edit any node directly in the n8n editor  
- Add new integrations using the “+” button  
- Test changes using **Execute Workflow**  
- Save once everything works correctly  

---

## 📤 Export / 📥 Import

You can export the workflow as a JSON file and import it into any n8n instance.  
Credentials must be reconfigured after import.

---

## 📈 Future Improvements

- Multi-city weather support  
- Rich email templates  
- AI‑generated weather summaries  
- Better error handling  
- Logging & monitoring  

---

## 📄 License

This project is licensed under the MIT License.



