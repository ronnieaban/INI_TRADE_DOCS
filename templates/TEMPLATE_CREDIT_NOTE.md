# CREDIT NOTE

Credit Note No.: {{CN_REF_NUMBER}}  
Date: {{ISSUE_DATE}}  
Ref. Invoice No.: {{ORIGINAL_INVOICE_REF}} (Dated: {{ORIGINAL_INVOICE_DATE}})  
Contract Ref. No.: {{RELATED_REF_NUMBER}}

| Issued By (Seller) | Issued To (Buyer) |
| :--- | :--- |
| {{SELLER_COMPANY_NAME}}<br>{{SELLER_ADDRESS}}<br>Tel / Email: {{SELLER_PHONE_EMAIL}}<br>Tax / License ID: {{SELLER_REG_TAX_ID}} | {{BUYER_COMPANY_NAME}}<br>{{BUYER_ADDRESS}}<br>Attn: {{BUYER_SIGNATORY_NAME}}<br>Tel / Email: {{BUYER_CONTACT}} |

### 1. Adjustment Reference

| Field | Details |
| :--- | :--- |
| Reason for Credit Note | {{ADJUSTMENT_REASON}} |
| Vessel / Barge and B/L No. | {{VESSEL_NAME_VOYAGE}}, B/L No.: {{BL_NUMBER}} |
| Supporting Certificate / SOF No. | {{SURVEY_REPORT_REF}} (Issued by {{INSPECTION_AGENCY}}) |
| Calorific Basis vs. Actual | Contract Base: {{GAR_BASE}} kcal/kg (ARB) / Certified Actual: {{ACTUAL_GAR}} kcal/kg (ARB) |
| Original Invoice Amount | {{CURRENCY}} {{ORIGINAL_INVOICE_AMOUNT}} |

### 2. Credit Breakdown

| No. | Description and Calculation | Unit | Quantity / Basis | Unit Credit Rate ({{CURRENCY}}) | Credit Amount ({{CURRENCY}}) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1 | {{COMMODITY_NAME}} ({{ADJUSTMENT_REASON}})<br>Calculation: {{ADJUSTMENT_CALCULATION_DETAIL}} | {{UNIT}} | {{ADJUSTED_QUANTITY}} | {{UNIT_ADJUSTMENT_RATE}} | {{TOTAL_ADJUSTMENT_AMOUNT}} |
| | Total Credit Note Amount | | | | {{CURRENCY}} {{TOTAL_ADJUSTMENT_AMOUNT}} |

Credit Amount in Words: Say {{TOTAL_ADJUSTMENT_IN_WORDS}}.

### 3. Revised Account Summary

| Summary | Amount ({{CURRENCY}}) |
| :--- | :--- |
| Original Invoice Amount ({{ORIGINAL_INVOICE_REF}}) | {{CURRENCY}} {{ORIGINAL_INVOICE_AMOUNT}} |
| Less: Credit Note ({{CN_REF_NUMBER}}) | ({{CURRENCY}} {{TOTAL_ADJUSTMENT_AMOUNT}}) |
| Net Revised Balance Payable | {{CURRENCY}} {{NET_REVISED_AMOUNT}} |

### 4. Settlement

This credit note will be settled by {{SETTLEMENT_METHOD}}.

For and on behalf of Seller:  
{{SELLER_COMPANY_NAME}}



____________________________________  
Name: {{SELLER_SIGNATORY_NAME}}  
Title: {{SELLER_SIGNATORY_TITLE}}  
Date: {{ISSUE_DATE}}


Acknowledged by Buyer:  
{{BUYER_COMPANY_NAME}}



____________________________________  
Name: {{BUYER_SIGNATORY_NAME}}  
Title: {{BUYER_SIGNATORY_TITLE}}  
Date: 
