# Supplier Invoice Processing



## Overview



Supplier Invoice Processing is a critical step in the SAP MM / Procure-to-Pay (P2P) cycle that completes the financial integration between Procurement and Accounts Payable. In SAP S/4HANA Cloud, creating a supplier invoice posts the vendor liabilities and generates a corresponding follow-on journal entry.



This activity demonstrates creating a supplier invoice with reference to a Purchase Order, displaying the invoice overview, and inspecting the generated follow-on accounting documents.



---



## 1. Create Supplier Invoice (Initial Entry)



The \*\*Create Supplier Invoice\*\* application is used to record incoming invoices received from suppliers against completed Purchase Orders or Goods Receipts.



### Key Invoice Fields



- \*\*Company Code:\*\* 1710

- \*\*Gross Invoice Amount \& Currency:\*\* USD

- \*\*Invoice Date \& Posting Date\*\*

- \*\*Reference Document:\*\* Purchase Order / Delivery Note

- \*\*Tax Details \& Payment Terms\*\*



\*\*Screenshot:\*\*  

`33\_Create\_Supplier\_Invoice\_Initial.png`



---



## 2. Display Supplier Invoice Overview



Once created, the supplier invoice document can be reviewed using the \*\*Display Supplier Invoice\*\* application.



### Key Overview Information



- \*\*Supplier Invoice Number\*\*

- \*\*Posting Status:\*\* Posted / Parked

- \*\*Invoicing Party / Supplier Details\*\*

- \*\*Header Amount \& Balance Verification\*\*



\*\*Screenshot:\*\*  

`34\_Display\_Supplier\_Invoice\_Overview.png`



---



## 3. Supplier Invoice PO Reference \& Line Items



The invoice references the underlying Purchase Order to ensure the relationship between the Purchase Order, Goods Receipt, and Supplier Invoice used during invoice verification.



### Line Item Matching



- \*\*Purchase Order Reference Number\*\*

- \*\*PO Item Number \& Material Description\*\*

- \*\*Invoiced Quantity \& Net Amount\*\*

- \*\*Tax Code \& G/L Account Assignments\*\*



\*\*Screenshot:\*\*  

`35\_Display\_Supplier\_Invoice\_PO\_Reference.png`



---



## 4. Invoice Follow-On Journal Entry



Posting a supplier invoice produces a related a financial Accounting Document (Journal Entry) in SAP General Ledger.



### A. General Information

Displays document header details including Document Number, Fiscal Year, Ledger Group, Posting Date, and Company Code.  

\*\*Screenshot:\*\* `36A\_Invoice\_Follow\_On\_Journal\_Entry\_General\_Information.png`



### B. Line Items

Shows debit and credit postings, typically debiting the GR/IR Clearing Account and crediting the Supplier Account (Accounts Payable).  

\*\*Screenshot:\*\* `36B\_Invoice\_Follow\_On\_Journal\_Entry\_Line\_Items.png`



### C. Totals and Taxes

Details total debit/credit balances, currency conversions, and tax amount breakdowns.  

\*\*Screenshot:\*\* `36C\_Invoice\_Follow\_On\_Journal\_Entry\_Totals\_and\_Taxes.png`



### D. Related Documents

Displays the document flow linking the Supplier Invoice to the Purchase Order, Material Document, and financial Journal Entry.  

\*\*Screenshot:\*\* `36D\_Invoice\_Follow\_On\_Journal\_Entry\_Related\_Documents.png`



---



## 5. Business Process Relevance



Supplier Invoice Processing ensures accurate financial accounting and procurement control by:



1\. Analyzing the relationship between the Purchase Order, Goods Receipt, and Supplier Invoice between PO, GR, and Invoice.

2\. Eliminating payment discrepancies and over-billing.

3\. Automatically updating Accounts Payable balances.

4\. Generating real-time financial audit trails via Journal Entries.



---



## 6. SAP MM / FI Concepts Demonstrated



- 3-Way Invoice Matching

- Supplier Invoice Posting

- Purchase Order Reference

- Accounts Payable Integration (MM-FI)

- GR/IR Clearing Account Settlement

- Follow-On Journal Entry Inspection



---



## 7. Project Outcome



This activity confirms the successful recording of supplier invoices and automatic posting of financial accounting entries, completing the operational phase of the Procure-to-Pay cycle in SAP S/4HANA Cloud.

