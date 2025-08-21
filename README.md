# 📊 FedEx Logistics Analysis Dashboard (Power BI)

## 🔎 Overview
This project analyzes FedEx Logistics Performance and their global pharmaceutical shipments to uncover trends in delivery, pricing, and delays.  
The dashboard provides key KPIs and insights to support supply chain optimization and decision-making.  

## 📌📊 Interactive Dashboard Charts

1. **Supplier Performance & Reliability**

Total Shipment Delays by Vendor and Country → Shows which vendors/countries face the most delays.

Shipment Delays by Vendor Type (RDC vs External) → Compares FedEx’s regional distribution centers with external vendors.

On-Time Shipment % (KPI Card) → Overall delivery performance metric.

Country with Most Shipment Delays (KPI Card) → Highlights the biggest bottleneck geography.

2. **Logistics & Cost Efficiency**

Median Freight Cost/Kg by Vendor Type → Compare freight efficiency of RDC vs external vendors.

Product Group vs Weight & Freight Cost → Identifies high-weight product groups and associated costs.

Median Freight Cost by INCO Term & Sub Classification → Shows effect of shipping contracts and product type on costs.

Sum of Freight Cost by Shipment Mode → Freight cost distribution across Air, Sea, Truck, Charter.

Median Freight Cost by Year → Cost efficiency trend over time.

Product Category with Maximum Freight Cost/Kg (KPI Card).

3. **Trend Analysis**

Median Freight Cost over Years → Cost fluctuation analysis.

Sum of Profit Margin over Years → Profitability trend.

Average Pack Price over Years → Procurement pricing trend.

4. **Profitability & Business Impact**

Sum of Line Item Value by Brand → Identifies top revenue-generating brands.

Sum of Line Item Value by Manufacturing Site → Manufacturing units’ contribution to shipments.

Median Profit Margin by Product Group → Profitability by product group.

Sum of Profit Margin by Country → Profitability contribution by geography.

Product Categories with Highest/Lowest Total Item Value Shipped (KPI Cards).

Top Manufacturing Unit by Profit Margin (KPI Card).

Top Manufacturing Unit by Quantity Shipped (KPI Card).

5. **Product Characteristics & Pricing**

Unit Price vs Profit Margin (Scatter) → Correlation of price with profitability.

Count of ID by Dosage Form & Sub Classification → Distribution of dosage forms and classifications.

Dosage Form with Highest Total Freight Cost (KPI Card).

Molecule/Test Type with Highest Shipped Line Quantity (KPI Card).

## 📷 Dashboard Preview
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/89909e08-5a56-4d39-8f0b-7fbdecdf3a4e" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/bfbbf6c0-4fcf-4465-955c-4e704018724d" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/a54d8343-7c56-4e4c-b9ec-0e54d635130b" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/2726cf6a-490c-4ada-a962-d750aaed942a" />


## 🛠️ Tools Used
- **Power BI Desktop** → Data cleaning, transformation, dashboard creation
- **Power Query** → ETL (removing nulls, handling text in weight column, transformations)
- **DAX** → Measures for KPIs (On-Time %, Median Pack Price, etc.)

## 🚀 How to Use
1. Download the `.pbix` file from this repo.
2. Open it in **Power BI Desktop** (free).
3. Explore filters, charts, and KPIs interactively.
4. The PDF Static version is also available for download from the repo.

## 💡 Key Insights

**1. Shipment Performance**

On-Time Shipment Rate: ~88.5%.

Nigeria has the most shipment delays, signaling a regional bottleneck.

RDCs vs External Vendors → External vendors show higher freight costs and more delays.

**2. Logistics & Cost**

Air freight dominates costs ($64M), followed by truck and air charter.

MRDT (Malaria Rapid Diagnostic Test) has the highest freight cost/kg (median ~185).

HIV Test Ancillary category also contributes high freight cost/kg (~22.8).

**3. Trends Over Time**

Median Pack Price is declining → stronger negotiations or market price drops.

Freight costs fluctuate but generally remain high → logistics inefficiency persists.

Profit margins show growth trend, suggesting overall business improvement.

**4. Profitability & Revenue**

Generic drugs dominate shipment value (~$1.3bn).

Mylan (Matrix, Nashik) is top manufacturing site in terms of profit margin (~$415M).

Aurobindo Unit III, India ships the highest product quantity (~47M units).

Highest shipped product category → Adult formulations (~$1.36bn).

Lowest shipped category → Malaria (~$0.35M).

**5. Product Characteristics**

Tablet-FDC dosage form incurs the highest freight cost (~$42.5M).

Most shipped molecule/test type: Lamivudine/Nevirapine/Zidovudine (~34M units).

Profit margin correlates positively with unit price, but not always linearly (some low-priced items still generate good margins).

✅**Overall, your dashboard tells a coherent business story:**

Where FedEx is losing efficiency (delays, freight costs, vendors).

Which regions and vendors are risk hotspots.

Which products, manufacturing sites, and dosage forms drive profitability.

How trends (pricing, freight, margins) are evolving over time.

## 📑 Deliverables
- `Fedex_Interactive Dashboard.pbix` → Main Power BI file
- `screenshots/` → Dashboard snapshots
- `Fedex_Interactive Dashboard.pdf` → Exported PDF for quick view

---

👨‍💻 Created by: Joysurya Bhattacharya  
📧 Contact: joysurya.bhattacharya@gmail.com
