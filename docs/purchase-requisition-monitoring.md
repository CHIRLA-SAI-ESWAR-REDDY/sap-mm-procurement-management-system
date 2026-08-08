\# Purchase Requisition Monitoring



\## Overview



The Monitor Purchase Requisition Items application provides an overview of purchase requisition items and their current procurement status.



This activity was performed using SAP S/4HANA Cloud Public Edition to monitor existing purchase requisition items.



\## SAP Application



\*\*App:\*\* Monitor Purchase Requisition Items



\## Process Performed



1\. Opened the Monitor Purchase Requisition Items application.

2\. Reviewed the available monitoring filters.

3\. Set the Display Currency to USD.

4\. Executed the search without restricting the other procurement filters.

5\. Retrieved the available Purchase Requisition Items.

6\. Reviewed procurement information including materials, plants, suppliers, quantities, values, delivery dates, release status, and purchase order status.

7\. Reviewed the monitoring dashboard and detailed list of purchase requisition items.



\## Available Filters



The application provides filters including:



\- Display Currency

\- Purchasing Organization

\- Purchasing Group

\- Material

\- Plant

\- Desired Supplier

\- Requisition Status

\- Delivery Date Interval

\- Delivery Status

\- Purchase Requisition Item

\- Material Group



\## Monitoring Results



The monitoring application returned \*\*1,672 Purchase Requisition Items\*\* in the available dataset.



Example procurement information observed included:



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



Other purchase requisition items showed different materials, quantities, suppliers, delivery dates, and procurement statuses.



\## Business Purpose



Purchase Requisition monitoring helps procurement users track the progress of requested materials and identify items requiring attention.



The monitoring view can help identify:



\- Overdue requisitions

\- Upcoming delivery dates

\- Released requisitions

\- Purchase orders created from requisitions

\- Desired suppliers

\- Material and plant requirements

\- Procurement values



\## Screenshot Evidence



The activity is documented using:



\- `../screenshots/purchase-requisition/29\_Monitor\_Purchase\_Requisition\_Items.png`

\- `../screenshots/purchase-requisition/30A\_Monitor\_Purchase\_Requisition\_Items\_Dashboard.png`

\- `../screenshots/purchase-requisition/30B\_Monitor\_Purchase\_Requisition\_Items\_List.png`



\## Learning Outcome



Through this activity, I gained practical experience in:



\- Monitoring Purchase Requisition Items

\- Using procurement monitoring filters

\- Reviewing large procurement datasets

\- Understanding requisition and delivery statuses

\- Tracking Purchase Order creation status

\- Reviewing procurement values

\- Connecting Purchase Requisitions with downstream purchasing activities



\## SAP MM Process Relationship



The monitoring activity provides visibility into the procurement process:



\*\*Purchase Requisition → Approval/Release → Purchase Order → Goods Receipt → Supplier Invoice\*\*



This demonstrates how SAP MM supports end-to-end procurement visibility.

