# 🏢 Davis Insurance CRM – Web-to-Lead Integration & Sales Automation

## 🚀 Overview
**Davis Insurance CRM** is a custom-built Salesforce application designed to streamline lead management and automate insurance sales workflows.  
It connects a branded web form directly to Salesforce using **Web-to-Lead**, enabling real-time capture, routing, and tracking of insurance leads through automated flows and dashboards.

This project demonstrates my ability to **design, configure, and automate** business processes within Salesforce using native tools and custom code integrations.

---

## 🧩 Key Features
- **Web-to-Lead Integration:** Connected a responsive HTML/CSS lead form to Salesforce’s Web-to-Lead endpoint for instant data capture.  
- **Automated Lead Routing:** Implemented Assignment Rules and Flow Builder to auto-assign leads to agents based on criteria (e.g., product type, state).  
- **Custom Object Model:** Designed schema relationships between Leads, Clients, Policies, and Agents using Lookup and Master-Detail relationships.  
- **Dynamic Lightning Pages:** Customized user interfaces with Lightning App Builder, related lists, and custom components.  
- **Data Validation & Security:** Configured validation rules, field-level security, and role-based access to maintain data integrity and compliance.  
- **Reports & Dashboards:** Built real-time dashboards to track lead sources, policy conversions, and agent performance metrics.  
- **Branding & UI:** Integrated a Davis Insurance logo, color scheme, and a modern layout for a cohesive user experience.

---

## 🧠 Technical Stack
- **Platform:** Salesforce Lightning Experience  
- **Tools & Features Used:**
  - Object Manager (Custom Objects, Record Types, Page Layouts)
  - Flow Builder / Process Builder
  - Web-to-Lead HTML Form Integration
  - Validation & Assignment Rules
  - Reports & Dashboards
  - Experience Cloud (for lead form & public landing page)
  - Lightning App Builder
- **Languages:** HTML, CSS, JavaScript (for form behavior)
- **Security:** Profiles, Permission Sets, Field-Level Security, Role Hierarchies

---

## 🏗️ Architecture Diagram
```plaintext
[Website Lead Form] → [Web-to-Lead Endpoint] → [Salesforce Lead Object]
     ↓
 [Flow Builder Automation] → [Agent Assignment / Email Alerts]
     ↓
 [Converted Leads] → [Accounts / Policies / Reports]
