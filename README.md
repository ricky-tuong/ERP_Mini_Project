# ERPNext Mini-Project: Small Retail Business Workflow

**Goal:** Simulate a small retail business workflow — from customer orders → inventory tracking → supplier replenishment → reporting dashboards — using ERPNext.

---

## Project Overview
This mini-project demonstrates end-to-end ERP functionality for a small retail business, including:

1. **Order-to-Cash (Sales Workflow)**
   - Capture customer orders  
   - Deliver items  
   - Generate and reconcile invoices  
   - Record customer payment  

2. **Stock Initialization**
   - Set opening stock using Stock Entries  
   - Track inventory in multiple warehouses  

3. **Procure-to-Pay (Purchase Workflow)**
   - Replenish inventory through Purchase Orders  
   - Receive items and update stock  
   - Record supplier invoices  

This project highlights **real-world ERP concepts** such as draft vs submitted workflow, inventory tracking, and financial reconciliation.

---

## Key Entities

| Entity Type | Name |
|-------------|------|
| Customer | Palmer Productions Ltd. |
| Supplier | Tech Supplies Inc. (Distributor) |
| Warehouses | Finished Goods – RRCO, Goods in Transit – RRCO, Stores – RRCO, Work in Progress – RRCO |
| Items | Laptop (SKU001), Backpack (SKU002), Headphones (SKU003) |

---

## Workflow Documentation

### 1. Sales Workflow (Order-to-Cash)

| Step | File | Description |
|------|------|------------|
| Draft Sales Order | `SALES_ORDER_DRAFT.pdf` | Initial planning of customer order |
| Submitted Sales Order | `SALES_ORDER.pdf` | Official order in ERP |
| Draft Delivery Note | `DELIVERY_NOTE_DRAFT.pdf` | Draft for review before delivery |
| Submitted Delivery Note | `DELIVERY_NOTE.pdf` | Confirms items shipped, updates inventory |
| Stock Summary After Delivery | `STOCK_SUMMARY_AFTER_DELIVERY.png` | Stock updated post-delivery |
| Sales Invoice | `SALES_INVOICE.pdf` | Invoice generated for customer |
| Payment Entry | `PAYMENT_ENTRY.pdf` | Payment entry created against invoice |
| Sales Invoice Paid | `SALES_INVOICE_PAID.png` | Invoice status updated to Paid, AR cleared |

---

### 2. Stock Initialization

| Step | File | Description |
|------|------|------------|
| Draft Stock Entry | `STOCK_ENTRY_DRAFT.png` | Planning step for initial stock quantities |
| Submitted Stock Entry | `STOCK_ENTRY.png` | Official opening stock recorded in ERPNext |

---

### 3️. Purchase Replenishment (Procure-to-Pay)

| Step | File | Description |
|------|------|------------|
| Draft Purchase Order | `PURCHASE_ORDER_DRAFT.png` | Initial planning of supplier order |
| Submitted Purchase Order | `PURCHASE_ORDER.png` | Official purchase order posted |
| Purchase Receipt | `PURCHASE_RECEIPT.png` | Items received from supplier, inventory updated |
| Final Stock Summary | `STOCK_SUMMARY_FINAL.png` | Updated stock after replenishment |

---

# Key Skills Demonstrated
- Created and managed **customers, suppliers, and items**  
- Managed **warehouses and stock levels**  
- Executed **Order-to-Cash workflow** (Sales → Delivery → Invoice → Payment)  
- Executed **Procure-to-Pay workflow** (Purchase → Receipt → Supplier Invoice → Stock)  
- Handled **draft vs submitted workflow**, reflecting real-world ERP processes  
- Reconciled **customer payments against invoices**  
- Used **Stock Summary / reporting** to track inventory  
- Developed transferable ERP skills applicable to **supply chain, logistics, and inventory management roles**  

---

## Notes for Recruiters / Reviewers
- Draft documents show **planning and review steps** before submission, simulating real business approvals.  
- Submitted documents show **official posted records**, impacting inventory and accounting.  
- PDFs are included for invoices to demonstrate **professional documentation**, while screenshots capture ERP interface steps and confirmations.

## Live Demo
Check out the live ERPNext system here: [My ERPNext Website](https://rrco-project.v.erpnext.com/desk)
