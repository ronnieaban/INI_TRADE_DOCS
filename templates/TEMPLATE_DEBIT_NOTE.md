# DEBIT NOTE

Debit Note No.: {{DN_REF_NUMBER}}  
Date: {{ISSUE_DATE}}  
Due Date: {{VALIDITY_DATE}}  
Ref. Invoice No.: {{ORIGINAL_INVOICE_REF}} (Dated: {{ORIGINAL_INVOICE_DATE}})  
Contract Ref. No.: {{RELATED_REF_NUMBER}}

| Issued By (Seller) | Billed To (Buyer) |
| :--- | :--- |
| {{SELLER_COMPANY_NAME}}<br>{{SELLER_ADDRESS}}<br>Tel / Email: {{SELLER_PHONE_EMAIL}}<br>Tax / License ID: {{SELLER_REG_TAX_ID}} | {{BUYER_COMPANY_NAME}}<br>{{BUYER_ADDRESS}}<br>Attn: {{BUYER_SIGNATORY_NAME}}<br>Tel / Email: {{BUYER_CONTACT}} |

### 1. Adjustment Reference

| Field | Details |
| :--- | :--- |
| Reason for Debit Note | {{ADJUSTMENT_REASON}} |
| Vessel / Barge and B/L No. | {{VESSEL_NAME_VOYAGE}}, B/L No.: {{BL_NUMBER}} |
| Supporting Certificate / SOF No. | {{SURVEY_REPORT_REF}} (Issued by {{INSPECTION_AGENCY}}) |
| Calorific Basis vs. Actual | Contract Base: {{GAR_BASE}} kcal/kg (ARB) / Certified Actual: {{ACTUAL_GAR}} kcal/kg (ARB) |
| Original Invoice Amount | {{CURRENCY}} {{ORIGINAL_INVOICE_AMOUNT}} |

### 2. Debit Breakdown

| No. | Description and Calculation | Unit | Quantity / Basis | Unit Charge Rate ({{CURRENCY}}) | Debit Amount ({{CURRENCY}}) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1 | {{COMMODITY_NAME}} ({{ADJUSTMENT_REASON}})<br>Calculation: {{ADJUSTMENT_CALCULATION_DETAIL}} | {{UNIT}} | {{ADJUSTED_QUANTITY}} | {{UNIT_ADJUSTMENT_RATE}} | {{TOTAL_ADJUSTMENT_AMOUNT}} |
| | Total Debit Note Amount | | | | {{CURRENCY}} {{TOTAL_ADJUSTMENT_AMOUNT}} |

Debit Amount in Words: Say {{TOTAL_ADJUSTMENT_IN_WORDS}}.

### 3. Revised Account Summary

| Summary | Amount ({{CURRENCY}}) |
| :--- | :--- |
| Original Invoice Amount ({{ORIGINAL_INVOICE_REF}}) | {{CURRENCY}} {{ORIGINAL_INVOICE_AMOUNT}} |
| Add: Debit Note ({{DN_REF_NUMBER}}) | {{CURRENCY}} {{TOTAL_ADJUSTMENT_AMOUNT}} |
| Net Revised Total Payable | {{CURRENCY}} {{NET_REVISED_AMOUNT}} |

### 4. Payment Instructions

Please remit {{CURRENCY}} {{TOTAL_ADJUSTMENT_AMOUNT}} on or before {{VALIDITY_DATE}} via {{PAYMENT_TERMS}} to the bank account below:

| Bank Details | Information |
| :--- | :--- |
| Beneficiary Name | {{SELLER_BANK_ACCOUNT_NAME}} |
| Bank Name | {{SELLER_BANK_NAME}} |
| Bank Branch Address | {{SELLER_BANK_ADDRESS}} |
| Account Number ({{CURRENCY}}) | {{SELLER_BANK_ACCOUNT_ACTIVE}} |
| SWIFT / BIC Code | {{SELLER_BANK_SWIFT}} |

For and on behalf of Seller:  
{{SELLER_COMPANY_NAME}}



____________________________________  
Name: {{SELLER_SIGNATORY_NAME}}  
Title: {{SELLER_SIGNATORY_TITLE}}  
Date: {{ISSUE_DATE}}


Accepted and confirmed by Buyer:  
{{BUYER_COMPANY_NAME}}



____________________________________  
Name: {{BUYER_SIGNATORY_NAME}}  
Title: {{BUYER_SIGNATORY_TITLE}}  
Date: 
