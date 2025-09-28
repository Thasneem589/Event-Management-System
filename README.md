# 🎉 Event Management System – Salesforce Capstone Project  

![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)
![Apex](https://img.shields.io/badge/Apex-Developer-orange?style=for-the-badge)
![LWC](https://img.shields.io/badge/Lightning%20Web%20Components-blueviolet?style=for-the-badge)
![Flows](https://img.shields.io/badge/Flows-Automation-brightgreen?style=for-the-badge)
![Reports](https://img.shields.io/badge/Reports-Dashboards-yellow?style=for-the-badge)

---

## 📌 Project Overview  
The Event Management System is a Salesforce-based solution designed to streamline the entire process of organizing events — from participant registrations to reporting. By automating event operations, it reduces errors, improves efficiency, and provides actionable insights through dashboards and reports.  

---

## 🎯 Problem Statement  
Event organizers often struggle with:  
- Handling registrations efficiently  
- Communicating with participants  
- Tracking sponsors and resources  
- Generating timely reports  

Without a centralized system, managing events becomes complex and prone to errors.  

This project solves these challenges by implementing a **Salesforce CRM solution** with automation, reporting, and user-friendly interfaces.  

---

## ✅ Objectives  
- Create and manage multiple events (date, venue, type, capacity).  
- Allow participant registration and track details.  
- Send automated confirmation emails and reminders.  
- Maintain records of sponsors and allocated resources.  
- Build reports and dashboards for performance tracking.  

---

## ⚙️ Key Features  

### 📅 Event Management  
- Store event details: name, type, venue, capacity, and dates.  

### 🧑‍🤝‍🧑 Participant Registration  
- Capture registrations as Leads/Contacts.  
- Track statuses: Registered → Confirmed → Attended.  

### 📧 Automated Communication  
- Send confirmation emails upon registration.  
- Trigger reminders before events.  

### 🎗 Resource & Sponsor Tracking  
- Allocate halls, logistics, and food arrangements.  
- Record sponsor contributions per event.  

### 📊 Reports & Dashboards  
- Compare registrations vs capacity.  
- Track event revenue & sponsor contributions.  
- Analyze participant demographics & attendance.  

---

## 🛠 Tech Stack  
- **Platform**: Salesforce CRM  
- **Objects**: Leads, Contacts, Accounts, Opportunities, Custom Objects (Events, Sponsors, Resources)  
- **Automation**: Flows, Validation Rules, Email Alerts  
- **Analytics**: Reports & Dashboards  

---

## 📂 Phase-wise Progress  

### 🔹 Phase 1 – Requirement Gathering & Design  
- Defined problem statement, scope, and objectives.  
- Designed data model (Events, Participants, Sponsors, Resources).  
- Documented workflows and features.  
📁 *Deliverables*: Requirement document, GitHub repo setup.  

---

### 🔹 Phase 2 – Salesforce Setup & Configuration  
- Created Lightning App: *Event Management System*.  
- Built custom objects: Event Details, Participants, Sponsors.  
- Configured fields, relationships, profiles, and permissions.  
📁 *Deliverables*: Salesforce setup screenshots, Phase 2 documentation.  

---

### 🔹 Phase 3 – Data Modeling  
- Implemented data model with relationships:  
  - `Event__c → EventRegistration__c (Master-Detail)`  
  - `Event__c → Sponsor__c (Lookup)`  
  - `Event__c → Resource__c (Lookup)`  
- Applied validation rules and prepared schema documentation.  
- Built event-based reports and dashboards.  
📁 *Deliverables*: Phase 3 Data Model PDF.  

---

### 🔹 Phase 4 – Process Automation (Admin)  
- **Validation Rules**: End Date > Start Date.  
- **Flows**: Booking form, record-triggered automation.  
- **Approval Process**: High-value bookings > ₹50,000 require manager approval.  
- **Email Alerts & Tasks**: Notify customers and assign agents.  
📁 *Deliverables*: Phase 4 Automation Document.  

---

### 🔹 Phase 5 – Apex Programming (Developer)  
- **BookingService**: Reusable validation logic.  
- **Triggers**: Prevent overlapping bookings.  
- **Batch Apex**: Mark overdue registrations.  
- **Queueable Apex**: Async discount calculation.  
- **Scheduled Apex**: Daily registration summary emails.  
- **Future Methods**: External API integration.  
- **Test Classes**: Coverage for all Apex components.  
📁 *Deliverables*: Phase 5 Apex Code & Documentation.  

---

### 🔹 Phase 6 – User Interface Development  
- Built **Lightning App Pages** with tabs for Events & Bookings.  
- Added **Home Dashboard** for upcoming events.  
- Developed **LWC Components**:  
  - Search events by date.  
  - Datatable with “Book Now” action.  
  - Apex integration for dynamic booking creation.  
📁 *Deliverables*: Phase 6 UI Development Document with screenshots.  

---

### 🔹 Phase 7 – External System Integration  
- Integrated with external **Insurance API** using Named Credentials.  
- Implemented Apex callouts via `InsuranceServiceApex`.  
- Booking triggers invoke API after record creation.  
📁 *Deliverables*: Integration documentation.  

---

### 🔹 Phase 8 – Data Management  
- Imported 50 demo booking records via Data Import Wizard.  
- Validated triggers and rules during import.  
📁 *Deliverables*: Data import logs & validation report.  

---

### 🔹 Phase 9 – Reporting & Security  
- Created reports: *Bookings by Event*, *Revenue by Event*, *Upcoming Bookings*.  
- Built dashboards with bar charts & tables.  
- Secured access with object-level permissions (Private for Bookings, Public for Events).  
- Assigned profiles for agents with restricted access.  
📁 *Deliverables*: Reports & Dashboard screenshots.  

---

### 🔹 Phase 10 – Final Presentation & Demo  
- Complete walkthrough of project features.  
- Demoed automation, reports, UI, and integrations.  

---

## 👨‍💻 Author  
**Syed Fathima Thasneem**  
- 🔗 [LinkedIn](https://www.linkedin.com/in/syed-fathima-thasneem-3bab10374)  

---

✨ *This Salesforce Capstone Project demonstrates end-to-end event management with automation, Apex programming, UI enhancements, and integrations — showcasing both Admin & Developer skills.*  
