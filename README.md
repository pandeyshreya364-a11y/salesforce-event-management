# 🎟️ Salesforce Event Management & Automated Ticketing System

## 📌 Overview
An end-to-end Salesforce implementation designed to manage event lifecycle, attendee registrations, and automated ticketing using Salesforce Automation and Security framework.

---

## 🏗️ Data Model & Schema Architecture
The core custom data model handles relational data using Master-Detail and Lookup relationships:

* **Event (`Event__c`)**: Stores event details, venue, date, and ticket capacity.
* **Attendee (`Attendee__c`)**: Captures attendee personal and contact information.
* **Ticket (`Ticket__c`)**: Junction object tracking specific event tickets linked to attendees.

---

## ⚙️ Process Automation (Salesforce Flows)

* **Trigger Type:** Record-Triggered Flow on Ticket Creation
* **Condition:** Checks Event Capacity before issuing ticket
* **Action:** Deducts available capacity and sends automated confirmation email to attendee

---

## 🔒 Security & Data Access Controls
* **OWD (Org-Wide Defaults):** Private for `Attendee__c` details.
* **Role Hierarchy & Sharing Rules:** Criteria-Based Sharing Rules for event managers.

---

## 🛠️ Tools & Technologies Used
* Lightning App Builder & Schema Builder
* Record-Triggered Flows & Validation Rules
* Salesforce Reports & Dashboards# salesforce-event-management
Salesforce implementation for event registration, automated ticketing via Record-Triggered Flows, and security # 🎟️ Salesforce Event Management & Automated Ticketing System

## 📌 Overview
An end-to-end Salesforce implementation designed to manage event lifecycle, attendee registrations, and automated ticketing using Salesforce Automation and Security framework.

---

## 🏗️ Data Model & Schema Architecture
The core custom data model handles relational data using Master-Detail and Lookup relationships:
