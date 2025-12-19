
---

## 🔄 Data Flow
1. **Raw data ingestion** into ADLS Gen2 (Bronze)
2. **Data cleansing & transformation** using Databricks (Silver)
3. **Optimized Parquet storage** in Silver container
4. **Gold layer views** created using `OPENROWSET` in Synapse Serverless SQL
5. **Analytics-ready data** exposed for Power BI

---

## 🧠 Key Features
- Serverless querying using **Synapse SQL**
- External data access via **OPENROWSET**
- Secure access using **Database Scoped Credentials**
- Modular SQL scripts for Gold layer
- GitHub-integrated Azure development workflow

---

## ▶️ How to Run This Project
1. Create **ADLS Gen2 storage account**
2. Upload AdventureWorks Parquet files to **Silver container**
3. Create:
   - Database Master Key (if not exists)
   - Database Scoped Credential
   - External Data Source
4. Execute SQL scripts in `/sql` folder
5. Validate Gold views
6. Connect Power BI (optional)

---

## 📊 Sample Gold Views
- `gold.calendar`
- `gold.customers`
- `gold.products`
- `gold.sales`
- `gold.returns`
- `gold.subcat`
- `gold.territories`

---

## 🔐 Security
- Uses **Database Scoped Credential**
- No secrets committed to GitHub
- Storage access controlled via Azure policies

---

## 🚀 Future Enhancements
- CI/CD using GitHub Actions
- Delta Lake optimization
- Incremental data loads
- Automated testing
- Monitoring with Azure Monitor

---

## 👤 Author
**Abhijeet Dande**  
Final Year Engineering Student  
Aspiring Data Engineer | Azure | Databricks  

---

## ⭐ If you find this project useful
Give it a ⭐ on GitHub!

