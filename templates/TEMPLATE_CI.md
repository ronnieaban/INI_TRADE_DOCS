# COMMERCIAL INVOICE

Invoice No.: {{CI_REF_NUMBER}}  
Date: {{ISSUE_DATE}}  
Contract / PI Ref.: {{RELATED_REF_NUMBER}}  
L/C or Payment Ref.: {{LC_OR_PAYMENT_REF}}

| Seller / Beneficiary / Shipper | Buyer / Consignee / Applicant | Notify Party |
| :--- | :--- | :--- |
| {{SELLER_COMPANY_NAME}}<br>{{SELLER_ADDRESS}}<br>Tel / Email: {{SELLER_PHONE_EMAIL}}<br>Tax / License ID: {{SELLER_REG_TAX_ID}} | {{BUYER_COMPANY_NAME}}<br>{{BUYER_ADDRESS}}<br>Attn: {{BUYER_SIGNATORY_NAME}}<br>Tel / Email: {{BUYER_CONTACT}} | {{NOTIFY_PARTY}} |

### 1. Vessel and Shipment Details

| Field | Details | Field | Details |
| :--- | :--- | :--- | :--- |
| Vessel / Barge Name | {{VESSEL_NAME_VOYAGE}} | Bill of Lading No. | {{BL_NUMBER}} |
| B/L Date | {{BL_DATE}} | Country of Origin | {{COUNTRY_OF_ORIGIN}} |
| Port of Loading | {{PORT_OF_LOADING}} | Port of Discharge | {{PORT_OF_DESTINATION}} |
| Delivery Terms | {{INCOTERMS}} {{NAMED_PORT}} (Incoterms 2020) | Packing | {{PACKING_TYPE}} |
| COA / Weight Cert. No. | {{SURVEY_REPORT_REF}} | Independent Surveyor | {{INSPECTION_AGENCY}} |

### 2. Quality and Price Adjustment Summary

| Parameter | Contract Basis | Certified Actual (COA) | Price Calculation |
| :--- | :--- | :--- | :--- |
| Gross Calorific Value (GCV) | {{GAR_BASE}} kcal/kg (ARB) | {{ACTUAL_GAR}} kcal/kg (ARB) | Adjusted Price = Base Price x (Actual GAR / Base GAR) |
| Total Moisture (TM ARB) | {{TM_GUARANTEED}}% | {{ACTUAL_TM}}% | Base Unit Price: {{CURRENCY}} {{BASE_UNIT_PRICE}} / {{UNIT}} |
| Ash (ADB) / Sulphur (ADB) | {{ASH_GUARANTEED}}% / {{TS_GUARANTEED}}% | {{ACTUAL_ASH}}% / {{ACTUAL_TS}}% | Final Invoiced Unit Price: {{CURRENCY}} {{UNIT_PRICE}} / {{UNIT}} |

### 3. Cargo Description and Invoice Calculation

| No. | Description of Goods | HS Code | B/L Weight ({{UNIT}}) | Final Unit Price ({{CURRENCY}}) | Total Amount ({{CURRENCY}}) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1 | {{COMMODITY_NAME}}<br>Certified GCV: GAR {{ACTUAL_GAR}} kcal/kg (ARB)<br>B/L No.: {{BL_NUMBER}} dated {{BL_DATE}}, Vessel: {{VESSEL_NAME_VOYAGE}} | {{HS_CODE}} | {{QUANTITY}} | {{UNIT_PRICE}} | {{TOTAL_AMOUNT}} |
| | Gross Invoice Value ({{INCOTERMS}} {{NAMED_PORT}}) | | {{QUANTITY}} | | {{CURRENCY}} {{TOTAL_AMOUNT}} |
| | Less: Advance Payment Received | | | | ({{CURRENCY}} {{ADVANCE_PAYMENT_RECEIVED}}) |
| | Net Total Amount Payable | | | | {{CURRENCY}} {{NET_PAYABLE_AMOUNT}} |

Net Amount in Words: Say {{TOTAL_AMOUNT_IN_WORDS}}.

### 4. Payment Instructions

Please remit {{CURRENCY}} {{NET_PAYABLE_AMOUNT}} in accordance with {{PAYMENT_TERMS}} to the bank account below:

| Bank Details | Information |
| :--- | :--- |
| Beneficiary Name | {{SELLER_BANK_ACCOUNT_NAME}} |
| Bank Name | {{SELLER_BANK_NAME}} |
| Bank Branch Address | {{SELLER_BANK_ADDRESS}} |
| Account Number ({{CURRENCY}}) | {{SELLER_BANK_ACCOUNT_ACTIVE}} |
| SWIFT / BIC Code | {{SELLER_BANK_SWIFT}} |

We certify that this Commercial Invoice is true and correct, that the coal described above is of Indonesian origin, and that the billed weight and calorific value match Bill of Lading No. {{BL_NUMBER}} and Certificate of Weight and Analysis No. {{SURVEY_REPORT_REF}} issued by {{INSPECTION_AGENCY}}.

For and on behalf of Seller:  
{{SELLER_COMPANY_NAME}}



____________________________________  
Name: {{SELLER_SIGNATORY_NAME}}  
Title: {{SELLER_SIGNATORY_TITLE}}  
Date: {{ISSUE_DATE}}
