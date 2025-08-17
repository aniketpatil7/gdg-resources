## Our Marketplace Tax Understanding, Backbone for Smart Tax

### 🚀 Payout Methods & Timing

> **Walmart pays sellers via ACH (no fees) to U.S. bank accounts.**  
> Third-party payout providers (eg. Payoneer, PingPong) are also supported — fees may apply.  
> Payments are typically **biweekly**, though new sellers face a ~14–21 day initial hold (~28 days per policy) :contentReference[oaicite:1]{index=1}. Poor account info or performance may delay or block payouts.

### 💳 Marketplace Wallet (U.S. Sellers Only)

!!! info "🏦 Marketplace Wallet (JPMorgan Chase)"
    Only **U.S.-registered sellers with an IRS tax ID** are eligible.
    - Wallet is an FDIC-insured deposit account at **JPMorgan Chase Bank, N.A.** (up to $250k) :contentReference[oaicite:2]{index=2}.
    - Administered by Walmart, Inc. — *Walmart is not a bank.*
    - **No hidden fees** for ACH transfers to a linked bank account.  
    Other sellers must use credit card or third-party payout options.

---

## 🧾 Tax Form Classifications

| Form         | Seller Type                                | Eligibility & Notes                                                       |
|--------------|--------------------------------------------|---------------------------------------------------------------------------|
| **W-9**      | U.S. sellers with EIN                      | May require IRS docs (CP575, 147c, CP148B)                               |
| **W-8ECI**   | Non-U.S. with EIN                          | Only if country supported; otherwise requires U.S. Tax ID                 |
| **W-8BEN-E** | Non-U.S. without EIN                       | For China, India, UK, Canada & others                                     |
| **W-8BEN**   | India & Mexico sole proprietors            | Mexico sellers limited to Mexico marketplace                              |

### 🇮🇳 Additional India Requirements

- **Non-sole proprietors**: utility bill/bank statement (<6 mo) + **GST certificate**
- **Sole proprietors**: rental agreement + NOC or recent utility, MSME registration, Shop & Establishment license, **GSTIN certificate**

---

## 🧭 Configuring Shipping Tax Codes

Retailers **must assign shipping sales tax codes** in Seller Center (*Settings → Partner Profile → Taxes*) to ensure correct tax collection.  
Hit **Save Tax Codes** to apply to your shipping methods.

*Consult a tax advisor if unsure.*

---

## 📄 Form 1099‑K Reporting

Form 1099‑K summarizes payment totals received for the calendar year from Walmart Marketplace.  
If your payouts meet IRS thresholds, you’ll receive and file this with your income tax :contentReference[oaicite:3]{index=3}.

---

## 📦 WFS Fees & Fulfillment Charges (as of April 2025)

### ⚙️ Highlights  

- **No signup or monthly fees**  
- Average fulfillment cost ~15% below competitors  
- No minimum or maximum inventory requirements

### ⚖️ Standard Fulfillment Fees

Based on greater of actual or dimensional weight:

| Weight       | Base Fee                |
|--------------|-------------------------|
| ≤ 1 lb        | $3.45                   |
| 2 lb          | $4.95                   |
| 3 lb          | $5.45                   |
| 4–20 lb       | $5.75 + $0.40/lb over 4 |
| 21–30 lb      | $15.55 + $0.40/lb over 21 |
| 31–50 lb      | $14.55 + $0.40/lb over 31 |
| ≥ 51 lb       | $17.55 + $0.40/lb over 51 |

**Extra unit fees**: apparel +$0.50 • hazardous +$0.50 • < $10 items +$1 • oversize +$3‑$20

### 🚛 Big & Bulky Freight

> Weight >150 lb or oversized: **$155 + $0.80/lb** over 90 lb

### 🏪 Storage Fees (monthly, per cu ft)

| Season         | < 365 days | > 365 days |
|----------------|-----------|-----------|
| Jan–Sept       | $0.75     | $2.25     |
| Oct–Dec (peak) | $0.75 (≤30d) *+ $1.50* if >30d | $2.25 |

### ⚠️ Inventory Corrections

- Missing label: $0.65  
- Incorrect/missing poly bag: $0.80

### 🔁 Return Processing

Same as standard fulfillment fees (table above)  
- Big & Bulky returns follow freight return rules  
- **Walmart covers return fees only if at fault**

### 🗑️ Disposal & Removal

| Weight Range  | Disposal Fee         | Removal Fee          |
|---------------|----------------------|----------------------|
| ≤ 2 lb         | $0.35                | $0.35 + $0.40/lb     |
| 3–500 lb       | $0.35 + $0.20/lb     | + $0.35 + $0.40/lb   |
- Hazardous items incur extra $0.50

### ➕ Optional Programs  

Enhance capabilities with:
- Cross-Border Imports  
- Multichannel Solutions  
- Multi‑Box shipping  
- Prep Services  
- Preferred Carrier Rates  
- Inventory Transfer  
- Serial Collection  

Use the **[WFS Cost Estimator]** for a full breakdown.

---

## 📄 WFS Shipment & Passport Integration

### 🔹 Required Documentation

- **BOL**: one per destination — includes shipment IDs, WFS center address, freight terms, seller & case info. LTL shipments must include NMFC code/class.  
- **Packing List** (optional): must match contents and be in a clear envelope outside the last-loaded pallet/case.

### ✨ Passport Issuance Process

1. Generate BOL → call Passport service → mint **Logistics Passport NFT** with metadata (BOL fields, tax form).  
2. Scan events at WFS (LabelVerified, PackagingVerified, etc.) trigger immutable on-chain logs tied to your Passport.

---

### 🔍 Fee & Tax Preview + Compliance Checker

Retailers can scan or upload labels, cartons, and specs to:

- Validate UPC labeling, carton specs, pallet compliance  
- Estimate WFS fees & storage/return costs  
- Forecast GST/VAT based on classification (e.g., W-8BEN-E)  
- Update Passport with `FeesEstimated` & `TaxEstimated` events — packaged into your "Final BOL + Passport" before shipping

---

**Key Takeaways:**  
- 📆 Biweekly payouts — new sellers face 14–21 day holds  
- 🏦 Marketplace Wallet available to U.S. sellers; ACH is free, FDIC-insured  
- 🧾 Detailed fee structure and optional services transparently outlined  
- 🚀 Passport integration adds compliance, fee preview, and immutable audit trail  

Let me know if you'd like charts, collapsible tax calculator examples, or dynamic WFS cost widgets!
::contentReference[oaicite:4]{index=4}
