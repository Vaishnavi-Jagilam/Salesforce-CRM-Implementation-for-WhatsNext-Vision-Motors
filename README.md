# 🚗 WhatsNext Vision Motors - Salesforce CRM Implementation

## 📘 Project Overview

**WhatsNext Vision Motors** is a pioneering force in the automotive industry, dedicated to transforming mobility through innovation and customer-focused solutions. This Salesforce CRM project aims to enhance the **customer ordering experience**, streamline operations, and improve service delivery through automation and smart integrations.

---

## 🎯 Project Objectives

- Simplify and automate the customer **vehicle ordering process**
- Improve **dealer assignment** through geolocation logic
- Ensure **accurate stock validation** at the time of order
- Automate **order status updates** based on stock availability
- Reduce manual workload for staff and enhance productivity

---

## ✨ Key Features

- 🔍 **Nearest Dealer Assignment**: Automatically assigns orders to the nearest dealer based on customer location.
- 🚫 **Stock Validation**: Prevents customers from placing orders for vehicles that are out of stock.
- 🔄 **Order Status Automation**:
  - If the vehicle is **in stock** → Status: `Confirmed`
  - If the vehicle is **out of stock** → Status: `Pending`
- 🛠️ **Batch Apex**: Periodic updates of stock levels and automated notifications.
- 📧 **Email Notifications**: Scheduled emails for test drive reminders and stock replenishment alerts.
- 🚘 **Test Drive & Service Tracking**: Track and manage test drives and service requests efficiently.

---

## 🧰 Technologies & Skills Used

- **Salesforce CRM**
- **Salesforce Lightning**
- **Salesforce Apex & Triggers**
- **Salesforce Security & Sharing**
- **Lightning App Builder**
- **Record-Triggered Flows**
- **Batch Apex & Scheduled Apex**

---

## 📦 Requirements

### Functional Requirements

- Store and manage:
  - Vehicle details
  - Stock availability
  - Dealer information
- Track:
  - Customer orders
  - Test drives
  - Service requests
- Automate:
  - Dealer assignment
  - Stock validation
  - Email notifications

### Apex & Trigger Requirements

- Apex triggers for:
  - Preventing order placement if vehicle is out of stock
  - Automatically assigning nearest dealer
- Use of **trigger handlers** for clean, modular code

### Batch Jobs

- Batch Apex job to:
  - Update vehicle stock levels
  - Change order statuses
- Scheduled Apex to:
  - Send emails for stock replenishment
  - Notify about pending orders

---

## 🧠 What You'll Learn

- Data Modeling in Salesforce
- Creating Fields & Relationships
- Using Lightning App Builder
- Designing Record-Triggered Flows
- Writing Apex Classes & Triggers
- Building Batch & Scheduled Apex Jobs
- Salesforce Security & Best Practices

---

## 📊 Project Stats

- **Total Epics**: 8  
- **Total Stories**: 16  
- **Subtasks**: 0 (Modular tasks may be introduced later)

---

## 🖥️ System Requirements

### Supported Browsers

- Google Chrome (Recommended)
- Mozilla Firefox
- Microsoft Edge
- Safari (macOS only)
- Internet Explorer 11 (Not recommended)

> 📌 Ensure at least **2 browsers** are installed for cross-browser testing.

### OS Compatibility

- Windows 10/11
- macOS (Latest versions)
- Linux (Limited support)
- ChromeOS (Browser-based usage)

### Hardware

- **Processor**: Intel Core i3 or higher
- **RAM**: Minimum 4GB (8GB+ recommended)
- **Storage**: Minimum 10GB free
- **Display**: 1366x768 (1920x1080 recommended)

### Network

- Stable internet connection (Minimum 3 Mbps)
- No VPN restrictions blocking Salesforce
- Whitelist: `.salesforce.com`, `.force.com`

---

## 🧑‍🏫 Mentorship

> _Note: No mentor assigned yet_

---

## 📂 Repository Structure (Suggested)

