<!-- Elegant Animated Header -->
<h1 align="center">
  🌾 AgriEdge Order & Shipment Automation  
  <br>
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=2E8B57&center=true&vCenter=true&width=550&lines=Salesforce+Order+Management+System;Shipment+Automation+Using+Apex;Smart+Agri+CRM+Platform+🌱" alt="typing-animation">
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Salesforce-Apex-blue?logo=salesforce&style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge" />
</p>

---

## 🌿 Project Overview  

**AgriEdge** is a Salesforce-based cloud automation project that optimizes **Order Management** and **Shipment Tracking** for agricultural businesses.  
It uses **Apex Triggers**, **Classes**, and **Custom Objects** to ensure seamless data flow and eliminate manual updates — enhancing reliability and efficiency in business operations.

---

## 🎯 Objectives

- Automate **order item calculations** and **shipment creation**  
- Maintain **real-time data integrity** between Orders, Order Items, and Shipments  
- Streamline processes for agriculture-based product management  
- Reduce manual intervention and ensure consistency using Apex automation  

---

## ⚙️ Features  

- ➕ Create **Orders** with multiple **Order Items**  
- 💰 Auto-calculate and update **Total Amount** dynamically  
- 🚚 Automatically generate **Shipment records** upon delivery  
- 🔁 Maintain synchronized updates across all related objects  
- 🧩 Built with **scalable and modular** Apex architecture  

---

## 🧠 Technology Stack  

| Technology | Description |
|-------------|-------------|
| **Salesforce Platform** | Core CRM and Development Environment |
| **Apex Programming** | Business Logic & Trigger Control |
| **SOQL** | Query Language for Object Relationships |
| **Lightning UI** | Interactive UI for Users and Admins |

---

## 🧾 Custom Objects  

| Custom Object | Description |
|----------------|-------------|
| `AgriEdge_Order__c` | Main order details |
| `AgriEdge_OrderItem__c` | Items within each order |
| `AgriEdge_Shipment__c` | Shipment information linked to an order |

---

## 🧩 Apex Components  

### 🔹 Triggers  
- `OrderItemTrigger` → Updates total order amount when order items are added or changed.  
- `OrderTrigger` → Creates shipments automatically when order status changes.  

### 🔹 Apex Classes  
- `OrderTotalUpdater` → Calculates total order amount dynamically.  
- `OrderStatusUpdater` → Updates order and shipment status automatically.  

---

## 🪜 Setup & Installation  

1. **Create Custom Objects:**  
   - `AgriEdge_Order__c`  
   - `AgriEdge_OrderItem__c`  
   - `AgriEdge_Shipment__c`  

2. **Add Custom Fields:**  
   - Order → `Total_Amount__c`, `Payment_Status__c`, `Order_Status__c`  
   - OrderItem → `Quantity__c`, `Unit_Price__c`, `Total_Price__c`  
   - Shipment → `AgriEdge_Order__c`, `Status__c`, `Tracking_Number__c`  

3. **Deploy Apex Components:**  
   - Go to **Setup → Apex Classes/Triggers → New**  
   - Paste the Apex code for triggers and helper classes  

4. **Testing Flow:**  
   - Create a new Order  
   - Add Order Items → observe auto total update  
   - Change Payment Status to *Paid* → Shipment auto-created  

---

## 🎥 Demo  

🎬 **[Watch Project Walkthrough Video](https://drive.google.com/file/d/1LdIP3dUUkC3OqKPmntUWEXcjDc2_RhL8/view?usp=sharing)**  
*(Shows complete process from Order creation to Shipment automation.)*

---

## 🖼️ Screenshots  

| Step | Description |
|------|--------------|
| 🧾 Order Creation | Creating a new AgriEdge Order |
| ➕ Adding Items | Adding Order Items to calculate totals |
| 💰 Auto Calculation | Auto-updating total amount |
| 🚚 Shipment Creation | Shipment created when status = Delivered |
| 📊 Final Dashboard | Orders, Items, and Shipments overview |

---

## 🔮 Future Enhancements  

- ✉️ Email Notifications to suppliers/customers on delivery  
- 🛰️ Real-time **Shipment Tracking** with Lightning Components  
- 📈 Dashboard Reports for Order & Shipment Analysis  
- ⚡ Salesforce **Flows Integration** to minimize Apex dependency  

---

## 👨‍💻 Author  

**H Rajanna Gari Anil Kumar**  
📍 *Anantapur, Andhra Pradesh*  
📧 [ania08333@gmail.com](mailto:ania08333@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/hranil)  
🌐 [Portfolio](https://anilhr.ccbp.tech/)

---

<p align="center">
  <img src="https://github.com/DenverCoder1/readme-typing-svg/blob/master/demo.gif" width="60" />
  <br>
  <b>⭐ Star this repository if you find it useful!</b>
  <br>
  <i>Built with dedication, precision, and Salesforce innovation ⚡</i>
</p>
