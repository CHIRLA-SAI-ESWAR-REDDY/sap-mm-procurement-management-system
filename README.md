# SAP MM Procurement Management System using SAP S/4HANA Cloud Public Edition

## 📌 Project Overview

The **SAP MM Procurement Management System** is an end-to-end procurement and inventory management project implemented using **SAP S/4HANA Cloud Public Edition**.

The project demonstrates a practical **SAP Materials Management (MM)** procurement lifecycle, covering master data, purchase requisitions, purchase contracts, purchase orders, goods receipts, inventory management, supplier invoice processing, accounting follow-on documents, and procurement monitoring/reporting.

The implementation was performed using the **SAP S/4HANA Cloud Public Edition trial environment** with realistic sample enterprise data and documented using SAP Fiori screenshots and technical documentation.

---

## 🎯 Project Objectives

- Understand the end-to-end SAP MM procurement lifecycle.
- Work with procurement-related master data.
- Manage purchase requisitions and monitor procurement requirements.
- Explore purchase contracts and their relationship with purchasing.
- Create and monitor purchase orders.
- Process goods receipts against purchase orders.
- Monitor inventory and material documents.
- Process supplier invoices.
- Analyze invoice-related accounting follow-on documents.
- Explore purchasing monitoring and reporting capabilities.
- Document SAP MM business processes with screenshots and technical documentation.

---

## 🏢 SAP Environment

| Component | Details |
|---|---|
| Platform | SAP S/4HANA Cloud Public Edition |
| Module | SAP Materials Management (MM) |
| Environment | SAP S/4HANA Cloud Trial |
| Company Code | 1710 – Velotics Inc. |
| Plant | Plant 1 US (1710) |
| Currency | USD |
| Procurement Focus | Procure-to-Pay and Inventory Management |

---

# 🔄 End-to-End Procurement Lifecycle

The project demonstrates the following core procurement flow:

```text
                    MASTER DATA
                        │
            ┌───────────┴───────────┐
            │                       │
       Material Master        Supplier Master
            │                       │
            └───────────┬───────────┘
                        ↓
              Purchase Requisition
                        ↓
                PR Monitoring
                        ↓
                Purchase Contract
                        ↓
                  Purchase Order
                        ↓
                  PO Monitoring
                        ↓
                  Goods Receipt
                        ↓
              Inventory Management
                        ↓
              Material Documents
                        ↓
                Supplier Invoice
                        ↓
              Accounting Document
                        ↓
             Purchasing Monitoring
                 & Reporting