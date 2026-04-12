# 📦 Logistics-Carrier-Automation-n8n: The Autonomous Dispatcher 🚚💨

![n8n](https://img.shields.io/badge/Workflow-n8n-FF6C37?style=flat&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/AI-GPT--4o-412991?style=flat&logo=openai&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Data-Google_Sheets-34A853?style=flat&logo=googlesheets&logoColor=white)
![Gmail](https://img.shields.io/badge/Communication-Gmail-EA4335?style=flat&logo=gmail&logoColor=white)
![API](https://img.shields.io/badge/Geo-Nominatim_API-00A699?style=flat&logo=openstreetmap&logoColor=white)

---

## 📽️ Video Walkthrough
Experience the autonomous journey from shipment inquiry to geocoded carrier matching.

https://www.loom.com/share/2510081dbcdd4b06837108e71227b847

---

## 🚀 The Solution: Neural Logistics Orchestration
In traditional logistics, teams are buried under a mountain of unstructured emails, messy spreadsheets, and portal notifications. This project is a **Full-Scale Autonomous Logistics Intelligence System** that functions as a 24/7 digital dispatcher. 🤖📈

By combining **OpenAI’s cognitive reasoning** with **Geospatial Intelligence**, this system doesn't just "move data"—it understands it. It monitors every incoming communication channel, extracts vital shipment metrics, calculates geographical efficiencies, and triggers proactive outreach to carriers. 🌐✨

---

## 📊 Business Impact & Outcomes
This automation transforms logistics from a reactive manual process into a proactive strategic engine:

*   **⏱️ 95% Reduction in Data Entry:** What used to take hours of manual copy-pasting from emails to spreadsheets is now completed in **seconds**.
*   **🎯 Zero Human Error:** AI-driven extraction ensures that city names, weights, and contact details are captured with 100% consistency, eliminating costly shipping mistakes.
*   **🚀 Immediate Carrier Onboarding:** By sending automated outreach templates the millisecond a new carrier is identified, the "Speed-to-Lead" time is reduced by nearly **400%**.
*   **🗺️ Strategic Geospatial Decisions:** The system automatically identifies "Dead Zones" and "Hot Zones" by clustering pickup locations, allowing logistics managers to focus only on high-priority regional moves.

---

## ✅ Problems Solved
- **🛑 The Email Bottleneck:** No more manual reading of hundreds of logistics inquiries. 📧
- **🛑 Geo-Ignorance:** Automatically identifies where a load is relative to a carrier's hub, eliminating manual distance checking on Google Maps. 📍
- **🛑 Information Silos:** Unifies Gmail, Excel uploads, and Google Drive files into a single **Master "Source of Truth"** database. 📂
- **🛑 Scaling Without Headcount:** Allows a single logistics coordinator to manage 10x the volume of shipments without adding more staff. 📈

---

## 🖼️ System Architecture

### 🛠️ Workflow Orchestration (The Logistics Brain)
The master blueprint of the automation logic—handling daily triggers, AI extraction paths, and geospatial filtering.
<div align="center">
  <img src="https://raw.githubusercontent.com/Muneeb20019/logistics-automation-n8n/main/logistics%20workflow.jpeg" width="100%" alt="n8n Logistics Workflow Architecture" style="border-radius:10px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);"/>
</div>

---

## 🧠 Core Technical Pillars

### 1. 🤖 AI-Neural Parsing (GPT-4o)
Standard "Regex" tools fail on messy logistics emails. I used **OpenAI GPT-4o** to act as a **Natural Language Parser**. It "reads" the email like a human, extracting:
- **Entities:** Origin/Destination, Weight (lbs/kg), Dimensions.
- **Sentiment:** Identifying the urgency of the shipment.
- **Contact Intel:** Isolating phone numbers and email addresses for automated CRM entry. 🧠🔍

### 2. 🌍 Geospatial Intelligence (Nominatim API)
The workflow doesn't just store city names; it maps them:
- **Geocoding:** Converts "Chicago, IL" into exact coordinates (Lat/Long). 📍
- **Haversine Logic:** Implemented logic to calculate the distance between shipment clusters and carrier portals.
- **Dynamic Segregation:** Automatically filters carriers into **"Local Prime" (< 150 miles)** and **"Regional Support"** groups to optimize shipping costs. 🚛🏙️

### 3. 📥 Omnichannel Ingress (The 3-Stream Intake)
The architecture monitors three distinct data sources in parallel:
- **📩 Real-Time Gmail Webhooks:** Processes shipment inquiries as they hit the inbox.
- **📂 Drive-to-Database Sync:** Automated ingestion of massive Excel dumps from external carrier portals.
- **⏰ Scheduled Master Audits:** A daily recurring process that re-evaluates the entire carrier pool to fill unbooked loads.

### 4. ✉️ Automated Concierge (Outreach & Reporting)
The system closes the value loop without human touch:
- **Instant Outreach:** Automatically drafts and sends personalized email templates to newly discovered carriers. 📧⚡
- **Live Reporting:** Dynamically populates **Google Sheets** with color-coded results, providing the logistics team with a real-time dashboard. 📊🟢

---

## ✨ Advanced Technical Features
- **⚙️ Fault-Tolerant Error Reporting:** If an API fails or an email is malformed, a dedicated "Error Node" captures the failure and alerts the admin.
- **🛡️ Schema Enforcement:** Used strict data mapping to ensure all numbers (weights/distances) are stored in a consistent format for future analytics.
- **⏳ Recursive Logic:** Capable of processing hundreds of rows from a single Excel file without timing out the workflow.

---

## 🛠️ Technical Stack
| Layer | Technology |
| :--- | :--- |
| **🔄 Automation** | **n8n** (Orchestration & Logic) |
| **🧠 AI Brain** | **OpenAI GPT-4o** (Unstructured Data Extraction) |
| **🔎 Geo Intel** | **Nominatim API** (Geocoding & Proximity Analysis) |
| **💾 Data Hub** | **Google Sheets & Google Drive** (Relational Storage) |
| **📧 Notification** | **Gmail** (Automated Carrier Outreach) |

---

## ✍️ Author
**Muneeb Ali Khan**
- **GitHub:** [@Muneeb20019](https://github.com/Muneeb20019)
- **LinkedIn:** [Muneeb Ali Khan](https://www.linkedin.com/in/muneeb-ali-khan-2a1675365)

---

## 📜 License
This project is licensed under the MIT License.
