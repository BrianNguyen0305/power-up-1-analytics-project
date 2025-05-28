
# Power Up: Real Analytics Project from Scratch

Welcome to the official dataset and materials repository for the YouTube mentorship series: **Power Up: Real Analytics Project from Scratch**. This series walks through a complete Power BI project with mentorship between an experienced analytics lead and a recent graduate. It includes real-world dirty data, business challenges, and Power BI modeling best practices.

## 📂 Folder Structure
```
power-up-analytics-project/
├── data/
│   ├── Calendar.csv
│   ├── Products_Enhanced.csv
│   ├── Stores.csv
│   ├── Sales.csv
│   ├── RegionHierarchy.csv
│   ├── Campaigns_Updated.csv
│   ├── ProductBundles.csv
│   ├── TaxRates.csv
│   ├── Sales_Dirty.csv
│   ├── Products_Dirty.csv
│   └── Stores_Dirty.csv
├── pbix/
│   └── PowerUp_Starter.pbix (coming soon)
├── README.md
├── LICENSE
└── session_notes/
    ├── episode0.md
    ├── episode1.md
    └── ...
```

## 📊 Project Overview
- 6-episode YouTube mentorship series
- Covers real-world analytics lifecycle
- Tools: Power BI, Power Query, Microsoft Fabric (optional)
- Realistic business scenarios with messy data

## ✅ What's Included
- Clean and dirty datasets
- Full transformation challenges (date format, missing values, duplicates, etc.)
- Bundles, tax rate logic, campaign effectiveness
- Region hierarchy and geo-enrichment

## 📁 Data Tables Explained
- **Calendar.csv** – Full calendar table with date, month, quarter, year, and flags for weekends/holidays.
- **Products_Enhanced.csv** – 50 SKUs with unique IDs, product names, categories, cost, and retail price.
- **Stores.csv** – 20 stores including region, manager name, and 3 employee names per store.
- **Sales.csv** – Transactional data with date, product/store ID, quantity sold, revenue, return flag, payment type, and campaign ID.
- **RegionHierarchy.csv** – Hierarchy table mapping region to division and country with geo-coordinates.
- **Campaigns_Updated.csv** – Marketing campaigns with budget, start/end dates, and targeted categories or bundles.
- **ProductBundles.csv** – Bundle definitions, mapping each bundle to 2–4 individual SKUs.
- **TaxRates.csv** – Tax percentage by region along with currency used.

## 🧪 Dirty Dataset Issues (Transformation Training)
These are real-world inspired issues used to train Power Query and cleaning techniques:

### `Sales_Dirty.csv`
- Mixed date formats (e.g., ISO 8601, MM/DD/YYYY)
- Null revenue values
- Extra space in column header: `"Units Sold "`
- Broken campaign or product ID links

### `Products_Dirty.csv`
- Category typo: `"Home & Ktchen"`
- Lowercase category: `"electronics"`
- Duplicate SKU row
- Price as invalid object (fixed in final)

### `Stores_Dirty.csv`
- Null manager name
- Inconsistent region format with whitespace (`" north"`, `"West "`)

## 🏗️ How to Use
1. Clone or download this repository
2. Open Power BI Desktop
3. Load the CSV files from the `data/` folder
4. Clean dirty versions in Power Query
5. Use the clean model to build relationships, DAX, and visuals

## 🎯 Learning Objectives
- Apply data cleaning and wrangling skills
- Design star schema and define relationships
- Calculate tax-adjusted metrics
- Build interactive dashboards

## 📺 YouTube Playlist (coming soon)
Stay tuned for the link to the official YouTube playlist.

## 🧑‍💻 Author
**Brian Nguyen** – Data & Analytics Lead @ SAP  
www.briannguyen.info

## 📜 License
This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.
