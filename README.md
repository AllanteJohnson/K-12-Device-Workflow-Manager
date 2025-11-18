# 📚 K-12 Device & Workflow Manager  
### Custom Odoo ERP App for School Device Inventory, Automation & AI Summaries

This project is a fully customized **Odoo ERP implementation** designed to streamline K–12 device management across schools.  
It includes custom data models, automation workflows, AI-powered summaries, reports, dashboards, and a user-ready interface — all created using **Odoo Studio**.

---

## 🚀 Features

### ✅ Custom Odoo ERP Data Model  
- Dedicated **Devices** model for school IT inventory  
- Custom fields:
  - Device Name  
  - Serial Number  
  - Device Type  
  - Status  
  - School  
  - Assigned User  
  - Last Check-In  
  - **AI Device Summary**

---

## 🤖 AI-Generated Device Health Summaries  

The system automatically creates a professional summary for each device using an **AI Text Field**.

**AI Prompt Used:**  
> Generate a short summary of this device using the fields in the record. Include the device name, type, serial number, assigned user, school, status, and last check-in date. Write it in a clean, professional tone for K-12 IT management.

✔ Runs on create/edit  
✔ Ensures consistency across all devices  
✔ Great for audits & IT workflow transparency  

---

## 🔄 Automation Workflows  

### 🟣 Automation Rule: Auto-Generate Device Summary  
- **Trigger:** On create and edit  
- **Apply on:** All Device records  
- **Action:** Update Record → Write AI Device Summary  

This automation ensures summaries stay up-to-date with every change.

---

## 📊 Dashboards & Reporting  

Built using Odoo’s graph and pivot tools:

- Device count by **device type**  
- Device distribution by **school**  
- Status dashboards  
- Graph visualizations with:
  - First dimension: Device Type  
  - Second dimension: Device Name  
  - Measure: Count or Sequence  

---

## 🧩 UI / UX Customization  

All UI components built in Odoo Studio:

- Organized form layouts  
- Tabs and columns  
- User assignment  
- Tags, notes, chatter  
- Archiving  
- Embedded AI field  

---

## 🏗️ Technical Stack

| Component | Technology |
|----------|------------|
| ERP Framework | **Odoo** |
| App Builder | **Odoo Studio** |
| Automations | Automated Server Actions |
| AI | Odoo AI Text Field |
| Reporting | Graph View, Pivot View, List View |
| Data Import | CSV |

---

## 📁 Recommended Repository Structure  

```
/screenshots
/sample_data
README.md
```

---

## 🧠 Project Summary  

A real K–12 IT asset management solution supporting:

- Chromebook programs  
- Teacher laptop/iPad programs  
- Device check-in/out  
- Inventory audits  
- School-wide device distribution tracking  

---

## 📝 Deliverables Completed  

- ✔ Custom ERP model for Devices  
- ✔ Full UI design  
- ✔ AI-driven summary generation  
- ✔ Automation rule  
- ✔ Dashboards  
- ✔ Sample data import  
- ✔ Documentation  

---

## 👨🏽‍💻 Author  

**Allante Johnson**  
Cybersecurity & IT Systems Specialist  

