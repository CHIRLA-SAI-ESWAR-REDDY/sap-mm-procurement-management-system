# SAP MM Procurement Management System

> **End-to-End Procurement, Inventory Management & MM-FI Integration using SAP S/4HANA Cloud Public Edition**

![SAP](https://img.shields.io/badge/SAP-S%2F4HANA%20Cloud-0FAAFF)
![Module](https://img.shields.io/badge/Module-SAP%20MM-0FAAFF)
![Process](https://img.shields.io/badge/Process-Procure--to--Pay-success)
![Evidence](https://img.shields.io/badge/SAP%20Screenshots-49-blue)
![Documentation](https://img.shields.io/badge/Documentation-Markdown-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

The **SAP MM Procurement Management System** is a practical SAP S/4HANA Cloud Public Edition implementation that demonstrates an end-to-end procurement lifecycle using **SAP Materials Management (MM)**.

The project models how an organization can manage purchasing requirements, procurement documents, goods receipts, inventory, supplier invoices, accounting follow-on documents, monitoring, and purchasing analysis within an integrated SAP environment.

Rather than focusing only on individual SAP transactions, the project connects the major business processes into a single **Procure-to-Pay (P2P)** workflow.

### Core Business Flow

```text
Business Requirement
        │
        ▼
Purchase Requisition
        │
        ▼
Purchase Order
        │
        ▼
Goods Receipt
        │
        ├──────────────► Inventory Update
        │
        ▼
Supplier Invoice
        │
        ▼
Accounting Document
        │
        ▼
Procurement Monitoring
        │
        ▼
Inventory & Purchasing Analysis