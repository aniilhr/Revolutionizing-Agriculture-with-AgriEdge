# 🚜 AgriEdge Order & Shipment Automation – Salesforce Project

This project is built on the Salesforce platform to streamline the **Order Management and Shipment Process** for an agriculture-focused enterprise using **custom objects** and **Apex triggers**.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Custom Objects](#custom-objects)
- [Apex Classes & Triggers](#apex-classes--triggers)
- [Installation](#installation)
- [Demo](#demo)
- [Screenshots](#screenshots)
- [Future Scope](#future-scope)
- [Author](#author)

---

## 🌾 Project Overview

**AgriEdge** is a custom Salesforce application designed to automate and manage the ordering and shipment of agricultural products. By leveraging Apex classes and triggers, the system ensures:

- Automatic total amount calculation per order.
- Shipment creation when an order is delivered.
- Efficient data updates across related objects.

---

## ✅ Features

- Create **AgriEdge Orders** and associate multiple **Order Items**.
- Automatically update **total order amount** when items are added or updated.
- When order status is set to **Delivered**, auto-create **Shipment**.
- Structured, reusable Apex code using helper classes.

---

## 🛠️ Technology Stack

| Technology | Purpose                  |
|------------|---------------------------|
| Salesforce | Platform                  |
| Apex       | Business Logic & Triggers |
| SOQL       | Query Language            |
| Lightning UI | Frontend Forms & Views  |

---

## 📂 Custom Objects

| Object Name                | Description                              |
|---------------------------|------------------------------------------|
| `AgriEdge_Order__c`        | Represents an order                     |
| `AgriEdge_OrderItem__c`    | Line items within an order              |
| `AgriEdge_Shipment__c`     | Shipment record linked to order         |

---

## 🧠 Apex Classes & Triggers

### 🔹 Triggers
- `OrderItemTrigger`: Updates total order amount
- `OrderTrigger`: Creates shipment when order status is "Delivered"

### 🔹 Apex Classes
- `OrderStatusUpdater`: Creates a shipment when an order is delivered
- `OrderTotalUpdater`: Calculates and updates total order amount

---

## 📦 Installation

1. Create the following custom objects:
   - AgriEdge_Order__c
   - AgriEdge_OrderItem__c
   - AgriEdge_Shipment__c

2. Add necessary fields:
   - Order → Status, Total Amount
   - OrderItem → Quantity, Unit Price
   - Shipment → Linked Order, Status

3. Add Apex Triggers and Classes:
   - `OrderItemTrigger`, `OrderTrigger`
   - `OrderStatusUpdater`, `OrderTotalUpdater`

4. Deploy and test in Salesforce Developer Org or Sandbox.

---

## 🎬 Demo

Watch the video walkthrough of the entire flow from creating an order to automatic shipment creation.

*Link to demo video: (https://drive.google.com/file/d/1LdIP3dUUkC3OqKPmntUWEXcjDc2_RhL8/view?usp=sharing)*

---

## 📸 Screenshots

- ✅ Order Creation Form
- ✅ Adding Order Items
- ✅ Auto-calculated Total
- ✅ Shipment Record Auto-Creation
- ✅ Final List Views for Orders & Shipments

---

## 🔮 Future Scope

- Add **Email Notification** to supplier/customer after shipment.
- Introduce **Delivery Tracking** via custom Lightning components.
- Enable **Reports and Dashboards** for Admins to monitor shipments.
- Use **Flows** to reduce Apex dependency for certain logic.

---

## 👨‍💻 Author

**H Rajanna Gari Anil Kumar**  
📧 ania08333@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/hranil)  
🌐 [Portfolio](https://anilhr.ccbp.tech/)

---

