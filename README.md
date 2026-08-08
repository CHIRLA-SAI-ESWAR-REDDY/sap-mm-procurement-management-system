# SAP MM Procurement Management System

## 📌 Project Overview

A practical SAP S/4HANA Cloud Public Edition project demonstrating an end-to-end procurement process and related SAP MM activities using realistic procurement data and Fiori applications.

The project focuses on understanding how SAP MM supports purchasing, inventory, master data, procurement monitoring, goods receipt, and related business processes.

---

## 🎯 Project Objectives

- Understand the SAP MM procurement lifecycle
- Work with SAP S/4HANA Cloud Fiori applications
- Create and analyze procurement documents
- Understand Material and Supplier Master Data
- Monitor Purchase Requisitions
- Process Goods Receipts
- Understand Purchase Contracts
- Document practical SAP MM activities with screenshots
- Maintain professional SAP project documentation using GitHub

---

## 🔄 Procure-to-Pay Process

The project covers the major Procure-to-Pay flow:

**Purchase Requisition → Purchase Order → Goods Receipt → Supplier Invoice**

The project also includes supporting procurement activities such as:

**Master Data → Purchase Contracts → Purchase Requisition Monitoring → Inventory Management**

---

## ✅ Completed SAP MM Modules

### 1. Procure-to-Pay

Completed activities:

- Manage Purchase Orders
- Create Purchase Order
- Purchase Order creation confirmation
- Post Goods Receipt
- Goods Receipt confirmation
- Create Supplier Invoice
- Supplier Invoice posting

### 2. Material Master

Completed activities:

- Material Master Basic Data
- Material Master Basic Data 2
- Sales/General Plant Data
- Material-related master data exploration

### 3. Inventory Management

Completed activities:

- Stock overview for a single material
- Material document overview
- Inventory-related stock analysis
- Goods Receipt posting and inventory update

### 4. Master Data

Completed activities:

- Vendor Master exploration
- Vendor search criteria
- Purchase Order list
- Purchase Order details
- Procurement master-data concepts

### 5. Purchase Requisition

Completed activities:

- Display Purchase Requisition
- Select Purchase Requisition
- Purchase Requisition search/help
- Purchase Requisition list
- Purchase Requisition details

### 6. Purchase Contract

Completed activities:

- Display Purchase Contract
- Purchase Contract search/help
- Purchase Contract list
- Related Purchase Order list
- Purchase Order header
- Purchase Order items

### 7. Goods Receipt Processing

Completed activities:

- Post Goods Receipt for Purchasing Document
- Purchase Order-based Goods Receipt
- Plant and Storage Location selection
- Unrestricted-Use stock posting
- Material Document generation
- Inventory update after Goods Receipt

### 8. Purchase Requisition Monitoring

Completed activities:

- Monitor Purchase Requisition Items
- Procurement monitoring filters
- Purchase Requisition status tracking
- Delivery status monitoring
- Purchase Order creation status
- Procurement value monitoring
- Monitoring dashboard
- Detailed Purchase Requisition item list

The monitoring application returned **1,672 Purchase Requisition Items** in the available dataset.

---

## 📊 Purchase Requisition Monitoring Example

Example data observed during monitoring:

| Field | Example |
|---|---|
| Purchase Requisition / Item | 0010000007 / 00010 |
| Material | 10000007 |
| Plant | Plant 1 US (1710) |
| Supplier | Carbon Tec Inc. (17300002) |
| Quantity | 11 PC |
| Net Value | 150,000 USD |
| Delivery Date | 02/24/2021 |
| Delivery Status | Overdue |
| Requisition Status | Release Completed (05) |
| Purchase Order Status | PO created (B) |

---

## 📸 Project Evidence

The project contains **30+ practical SAP screenshots** covering the completed SAP MM activities.

### Procure-to-Pay

- 01_Manage_Purchase_Orders.png
- 02_Create_Purchase_Order.png
- 03_Purchase_Order_Created.png
- 04_Post_Goods_Receipt.png
- 05_Goods_Receipt_Posted.png
- 06_Create_Supplier_Invoice.png
- 07_Supplier_Invoice_Posted.png

### Inventory Management

- 08_Stock_Single_Material.png
- 09_Material_Documents_Overview.png
- 28_Goods_Receipt_Posted.png

### Material Master

- 10_MaterialMaster_BasicData1_A.png
- 10_MaterialMaster_BasicData1_B.png
- 11_MaterialMaster_BasicData2_A.png
- 11_MaterialMaster_BasicData2_B.png
- 12_MaterialMaster_SalesGeneralPlant_A.png
- 12_MaterialMaster_SalesGeneralPlant_B.png

### Master Data

- 13_Vendor_Master_Find_Screen.png
- 14_Vendor_Master_Search_Criteria.png
- 15_Purchase_Order_List.png
- 16_Purchase_Order_Details.png

### Purchase Requisition

- 17_Display_Purchase_Requisition_Advanced.png
- 18_Select_Purchase_Requisition.png
- 19_Purchase_Requisition_Search_Help.png
- 20_Purchase_Requisition_List.png
- 21_Purchase_Requisition_Details.png
- 29_Monitor_Purchase_Requisition_Items.png
- 30A_Monitor_Purchase_Requisition_Items_Dashboard.png
- 30B_Monitor_Purchase_Requisition_Items_List.png

### Purchase Contract

- 22_Display_Purchase_Contract_Initial_Screen.png
- 23_Purchase_Contract_Search_Help.png
- 24_Purchase_Contract_List.png
- 25_Manage_Purchase_Orders_List.png
- 26_Purchase_Order_Header.png
- 27_Purchase_Order_Items.png

---

## 📚 Documentation

Detailed documentation is available in the `docs` directory:

```text
docs/
├── goods-receipt-processing.md
├── inventory-management.md
├── master-data.md
├── material-master.md
├── purchase-contract.md
├── purchase-requisition.md
└── purchase-requisition-monitoring.md