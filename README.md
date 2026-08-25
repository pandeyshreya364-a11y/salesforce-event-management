# 🎟️ Salesforce Event Management System

## 📌 Overview
An end-to-end Salesforce implementation designed to manage event lifecycle, attendee registrations, and automated ticketing using Salesforce Automation and Security framework.

---

## 🏗️ Data Model & Schema Architecture
- **Event (`Event__c`)**: Parent object storing venue, date, and ticket capacity.
- **Attendee (`Attendee__c`)**: Stores attendee personal contact information.
- **Ticket (`Ticket__c`)**: Junction object linking Attendees to specific Events.

---

## ⚙️ Process Automation (Salesforce Flows)
- **Record-Triggered Flow:** Triggers on Ticket Creation to validate event capacity.
- **Automated Actions:** Deducts remaining capacity and sends confirmation emails to attendees.
- **Validation Rules:** Prevents ticket booking if event capacity is full.

---

## 🔒 Security & Analytics
- **OWD (Org-Wide Defaults):** Set to Private for sensitive attendee data.
- **Sharing Rules:** Configured Criteria-Based Sharing for event managers.
- **Reports & Dashboards:** Custom Summary Reports tracking ticket sales and capacity.

---

## 🛠️ Tools & Technologies Used
- Lightning App Builder & Schema Builder
- Record-Triggered Flows & Validation Rules
- Salesforce Reports & Dashboards
