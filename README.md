# K–12 Device & Workflow Manager  
### Custom Odoo ERP Implementation for School Device Tracking  

This project is a fully-custom Odoo app designed to manage K–12 device inventory, automate IT workflows, and generate AI-powered device health summaries.  
Everything was built using **Odoo Studio**, **Odoo Automations**, and the **Odoo AI Field framework** — no custom Python modules required.

---

## 🚀 Features  

### ✔️ Custom ERP Device Model  
Includes fields for:

- Device Name  
- Serial Number  
- Device Type  
- Status  
- School  
- Assigned User  
- Last Check-In  
- **AI Device Summary (auto-generated)**  

#### Model Setup Screenshot  
![Model Screenshot](https://raw.githubusercontent.com/AllanteJohnson/-K-12-Device-Workflow-Manager/main/1.png)

---

## ⚙️ Workflow Automations  

### ✔️ AI-Generated “Device Summary”  
Whenever a device is created or updated, Odoo automatically:

1. Reads all device fields  
2. Sends the data to the AI Text field  
3. Writes a clean, professional summary  

#### Automation Rule Screenshot  
![Automation Screenshot](/2.png)

---

## 🧠 AI Summary Prompt  
The built-in AI field uses the following custom prompt:

> **"Generate a short summary of this device using the fields in the record. Include the device name, type, serial number, assigned user, school, status, and last check-in date. Write it in a clean, professional tone for K–12 IT management."**

#### AI Field Configuration Screenshot  
![AI Field Screenshot](./3.png)

---

## 🧱 Data Model & Form Design  
Designed in Odoo Studio with clean layout and user-friendly structure.

#### Studio Form Editor Screenshot  
![Form Editor](./4.png)

#### Completed Device Form Screenshot  
![Device Form](./5.png)

---

## 📊 Interactive Analytics Dashboards  
Includes:

- Device Type Breakdown  
- Status Distribution  
- School-Level Device Counts  

#### Analytics Graph Screenshot  
![Analytics Graph](./6.png)

---

## 🛠️ Technical Architecture  

| Component         | Description                              |
|------------------|------------------------------------------|
| Odoo Studio      | Custom models, views, menus              |
| Odoo Automations | On-create & on-write triggers            |
| Odoo AI Field    | Auto-generated device summaries          |
| Graph Dashboard  | Device insights & categories             |
| Odoo ORM (Studio)| No Python required                       |

---

## 🧾 Project Highlights (Resume Ready)

- Customized Odoo ERP framework for K–12 device inventory & asset tracking  
- Built relational data models, forms, views, and menus  
- Implemented complete end-to-end workflows using Odoo automations  
- Integrated AI-powered summaries for device health reporting  
- Developed interactive analytics dashboards  
- Delivered implementation documentation and a clean, user-ready interface  

---

## 🙌 Author  
**Allante Johnson**  
Technical Implementation • IT Asset Management • Odoo Implementations • K–12 Technology  
