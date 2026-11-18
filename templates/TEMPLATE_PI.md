# PROFORMA INVOICE

Proforma Invoice No.: {{PI_REF_NUMBER}}  
Date: {{ISSUE_DATE}}  
Valid Until: {{VALIDITY_DATE}}  
Contract / Offer Ref.: {{RELATED_REF_NUMBER}}

| Seller / Beneficiary | Buyer / Consignee |
| :--- | :--- |
| {{SELLER_COMPANY_NAME}}<br>{{SELLER_ADDRESS}}<br>Tel / Email: {{SELLER_PHONE_EMAIL}}<br>Tax / License ID: {{SELLER_REG_TAX_ID}} | {{BUYER_COMPANY_NAME}}<br>{{BUYER_ADDRESS}}<br>Attn: {{BUYER_SIGNATORY_NAME}}<br>Tel / Email: {{BUYER_CONTACT}} |

### 1. Shipment Details

| Field | Details |
| :--- | :--- |
| Commodity | {{COMMODITY_NAME}} |
| Country of Origin | {{COUNTRY_OF_ORIGIN}} |
| Delivery Terms | {{INCOTERMS}} {{NAMED_PORT}} (Incoterms 2020) |
| Port of Loading | {{PORT_OF_LOADING}} |
| Port of Discharge | {{PORT_OF_DESTINATION}} |
| Shipment / Laycan | {{SHIPMENT_SCHEDULE}} |
| Partial / Transshipment | Partial Shipment: {{PARTIAL_SHIPMENT_ALLOWED}} / Transshipment: {{TRANSSHIPMENT_ALLOWED}} |
| Packing and Survey | {{PACKING_TYPE}}, weight and quality final at Loading Port by {{INSPECTION_AGENCY}} |

### 2. Description of Goods and Value

| No. | Description of Goods | HS Code | Quantity ({{UNIT}}) | Unit Price ({{CURRENCY}}) | Total Amount ({{CURRENCY}}) |
| :---: | :--- | :---: | :---: | :---: | :---: |
| 1 | {{COMMODITY_NAME}}<br>Base GCV: GAR {{GAR_BASE}} kcal/kg (ARB), Rejection below {{GAR_REJ}} kcal/kg<br>TM (ARB): {{TM_GUARANTEED}}% / Ash (ADB): {{ASH_GUARANTEED}}% / TS (ADB): {{TS_GUARANTEED}}% / HGI: {{HGI_GUARANTEED}}<br>Quantity Tolerance: +/- {{TOLERANCE_PERCENT}}% at Seller's or Vessel's option | {{HS_CODE}} | {{QUANTITY}} | {{UNIT_PRICE}} | {{TOTAL_AMOUNT}} |
| | Total Proforma Value ({{INCOTERMS}} {{NAMED_PORT}}) | | {{QUANTITY}} | | {{CURRENCY}} {{TOTAL_AMOUNT}} |

Amount in Words: Say {{TOTAL_AMOUNT_IN_WORDS}}.

### 3. Payment Terms and Bank Details

Payment Terms: {{PAYMENT_TERMS}}

| Bank Details | Information |
| :--- | :--- |
| Beneficiary Name | {{SELLER_BANK_ACCOUNT_NAME}} |
| Bank Name | {{SELLER_BANK_NAME}} |
| Bank Address | {{SELLER_BANK_ADDRESS}} |
| Account Number ({{CURRENCY}}) | {{SELLER_BANK_ACCOUNT_ACTIVE}} |
| SWIFT / BIC Code | {{SELLER_BANK_SWIFT}} |

For and on behalf of Seller:  
{{SELLER_COMPANY_NAME}}



____________________________________  
{{SELLER_SIGNATORY_NAME}}  
{{SELLER_SIGNATORY_TITLE}}


Confirmed and accepted by Buyer:  
{{BUYER_COMPANY_NAME}}



____________________________________  
{{BUYER_SIGNATORY_NAME}}  
{{BUYER_SIGNATORY_TITLE}}
