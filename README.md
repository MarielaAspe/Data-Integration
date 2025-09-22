# Data Analytics & Visualization Portfolio

This repository contains my projects demonstrating **data integration, transformation, and visualization** using Pentaho and IBM Db2.

- **Google Sheets** – raw dataset used as source  
- **Pentaho Data Integration (PDI/Kettle)** – ETL workflows, transformations, and reports  
- **IBM Db2** – cloud database where transformed data is loaded  

---

## 📂 Contents

### GoogleSheet/
- `ExcelInventory(1).xlsx` – exported dataset used as input for ETL

### Pentaho/
- **Transformations/** – `.ktr` files for extraction, cleaning, and transformation  

---

## 📊 Dataset Details

| Column Name       | Description                                |
|------------------|--------------------------------------------|
| BranchPlantKey    | Identifier for the branch or plant         |
| Date              | Transaction date                           |
| ItemMasterKey     | Unique key for each item in inventory      |
| TransTypeKey      | Transaction type identifier                |
| CustVendorKey     | Customer or vendor identifier              |
| UnitCost          | Cost per unit of the item                  |
| Currency          | Currency of the transaction                |
| Quantity          | Number of units involved in the transaction |

---

## 💾 Data Source & Destination

- **Source:** Google Sheets / Excel files  
- **Destination:** IBM Db2 cloud database  
- **ETL & Visualization Tool:** Pentaho Data Integration (PDI/Kettle) for processing data and creating reports/dashboards  
