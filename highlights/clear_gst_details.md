# Clear GST Details on Sales Invoices

[← Back to Release Notes](../README.md)

## Overview

Sales invoices now display GST (Goods and Services Tax) breakdowns with automatic tax calculations based on transaction type and location.

---
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/d92b55b6-06d4-4b60-a32e-401ce961e60a" />


---

### Automatic Tax Calculation
- **Intrastate Transactions**: Automatically applies CGST + SGST when buyer and seller are in the same state
- **Interstate Transactions**: Automatically applies IGST when buyer and seller are in different states


## Usage Examples

### Intrastate Transaction
- **Scenario**: Hospital in Maharashtra billing patient in Maharashtra
- **Tax Application**: CGST (9%) + SGST (9%) = 18%
- **Display**: Shows separate CGST and SGST components

### Interstate Transaction
- **Scenario**: Hospital in Maharashtra billing patient in Gujarat
- **Tax Application**: IGST (18%)
- **Display**: Shows IGST component only
