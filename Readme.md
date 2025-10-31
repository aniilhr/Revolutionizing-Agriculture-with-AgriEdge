<!-- Animated Header -->
<h1 align="center">
  🚜 AgriEdge Order & Shipment Automation  
  <br>
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=1000&color=00C853&center=true&vCenter=true&width=600&lines=Salesforce+Order+%26+Shipment+Automation;Apex+Trigger+%26+Class+Implementation;Smart+Agri+CRM+System+🌾" alt="Typing Animation" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Salesforce-Apex-blue?logo=salesforce" />
  <img src="https://img.shields.io/badge/Platform-Cloud%20CRM-lightblue?logo=icloud" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
  <img src="https://img.shields.io/badge/Language-Apex-yellow" />
</p>

---

## 🌾 Project Overview

**AgriEdge** is a Salesforce-based automation project that streamlines **Order Management and Shipment Processing** for an agricultural enterprise.  
The system leverages **Apex triggers, classes, and custom objects** to automate total calculations and shipment creation — reducing manual effort and improving business efficiency.

---

## ✅ Features

- 🌱 Create **AgriEdge Orders** and link multiple **Order Items**
- 💰 Auto-calculate **total order amount** when items are added or updated  
- 🚚 Auto-create **Shipment** when an order status is set to *Delivered*  
- ♻️ Reusable and modular **Apex Helper Classes**  
- 🧠 Real-time data consistency between **Orders**, **OrderItems**, and **Shipments**

---

## 🛠️ Technology Stack

| Technology | Purpose |
|-------------|----------|
| **Salesforce** | Cloud CRM Platform |
| **Apex** | Business Logic & Trigger Processing |
| **SOQL** | Querying Salesforce Data |
| **Lightning UI** | Forms and Record Views |

---

## 📂 Custom Objects

| Object Name | Description |
|--------------|--------------|
| `AgriEdge_Order__c` | Represents an agricultural order |
| `AgriEdge_OrderItem__c` | Line items associated with an order |
| `AgriEdge_Shipment__c` | Shipment details linked to an order |

---

## 🧠 Apex Classes & Triggers

### 🔹 Triggers
- `OrderItemTrigger` → Updates total order amount when items are added or changed  
- `OrderTrigger` → Creates shipment automatically when order is delivered  

### 🔹 Apex Classes
- `OrderStatusUpdater` → Handles shipment creation based on order status  
- `OrderTotalUpdater` → Calculates and updates total order value  

---

## ⚙️ Installation Guide

1. **Create Custom Objects**
   - AgriEdge_Order__c  
   - AgriEdge_OrderItem__c  
   - AgriEdge_Shipment__c  

2. **Add Fields**
   - **Order** → Status, Total Amount  
   - **OrderItem** → Quantity, Unit Price  
   - **Shipment** → Linked Order, Status  

3. **Deploy Apex Classes and Triggers**
   - Add the Apex classes and triggers in Salesforce Setup → Apex Classes / Triggers.

4. **Test the Flow**
   - Create a new order → Add items → Mark order as “Delivered” → Shipment auto-creates.

---

## 🎬 Demo

🎥 **[Watch Demo Video Here](https://drive.google.com/file/d/1LdIP3dUUkC3OqKPmntUWEXcjDc2_RhL8/view?usp=sharing)**  
> Demonstrates the complete flow from creating an order to automatic shipment creation.

---

## 📸 Screenshots

| Step | Screenshot |
|------|-------------|
| 🧾 Order Creation | ![Order](https://img.icons8.com/color/48/000000/order-history.png) |
| ➕ Add Order Items | ![Item](https://img.icons8.com/color/48/000000/add-to-cart.png) |
| 💰 Auto Total Update | ![Calc](https://img.icons8.com/color/48/000000/calculator.png) |
| 🚚 Shipment Auto-Creation | ![Ship](https://img.icons8.com/color/48/000000/delivery.png) |
| 📊 Final View | ![List](https://img.icons8.com/color/48/000000/list.png) |

---

## 🔮 Future Scope

- ✉️ Email notifications to suppliers/customers after shipment creation  
- 🛰️ Real-time **delivery tracking** using Lightning Components  
- 📊 Add **Reports and Dashboards** for analytics  
- ⚡ Replace Apex logic with **Flows** for easier maintenance  

---

## 👨‍💻 Author

**H Rajanna Gari Anil Kumar**  
📍 Anantapur, Andhra Pradesh  
📧 [ania08333@gmail.com](mailto:ania08333@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/hranil)  
🌐 [Portfolio](https://anilhr.ccbp.tech/)  

---

<p align="center">
  <b>⭐ If you liked this project, don't forget to star the repository! ⭐</b>  
  <br><br>
  <img src="https://github.com/rajaprerak/rajaprerak/blob/master/assets/animated-flame.gif" width="60" height="60" />
</p>
