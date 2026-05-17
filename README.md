# Teacher Salaries in Portugal: A Data-Driven Analysis of Macroeconomic Alignment

This repository contains the technical artifacts developed for the master’s dissertation:

> **“Teacher Salaries in Portugal: A Data-Driven Analysis of Macroeconomic Alignment”**

The project investigates the extent to which teachers’ and school heads’ statutory salaries in Portugal evolved in alignment with key macroeconomic indicators between 2021 and 2024.

---

# 1. Research Question

To what extent do teachers’ and school heads’ salaries in Portugal reflect and evolve in relation to key macroeconomic indicators?

---

# 2. Objectives

- Analyze the evolution of teachers’ and school heads’ salaries in Portugal using open data from Eurydice, complemented by macroeconomic indicators from Eurostat and Statistics Portugal (INE - National Institute of Statistics);
- Examine the relationships between salary evolution and key national economic indicators, assessing their coherence;
- Design and validate a Power BI dashboard as a data-driven artifact that integrates educational and economic data, supporting evidence-based analysis and policymaking in education.

---

# 3. Methodology

The project follows the Design Science Research Methodology (DSRM), supported by a Kimball-based dimensional modeling approach implemented in Microsoft Fabric and Power BI.

The analytical architecture includes:
- Data integration and staging procedures;
- Dimensional data warehouse modeling;
- Semantic layer development;
- Interactive analytical dashboard.

---

# 4. Repository Structure

```text
Teacher_Salaries_Portugal_Macro_Alignment/
│
├── 01_DataSources/        Raw educational and macroeconomic datasets
├── 02_Staging/            ETL staging and validation procedures
├── 03_DataWarehouse/      Dimensional warehouse and loading processes
├── 04_SemanticModel/      Semantic layer and analytical metadata
├── 05_PowerBI/            Power BI dashboard artifact
└── README.md
```

---

# 5. Main Technologies

- Microsoft Fabric
- Dataflows Gen2
- Data Pipelines
- SQL
- Dimensional Modeling (Kimball)
- Power BI
- DAX

---

# 6. Main Analytical Areas

The dashboard supports the analysis of:
- Nominal and real salary evolution;
- Inflation-adjusted remuneration;
- Salary positioning relative to wages and GDP;
- Cost-of-living and housing dynamics;
- European comparative analysis using PPS-adjusted salaries.

---

# 7. Data Sources

The analysis integrates data from:
- Eurydice / EACEA
- Eurostat
- Statistics Portugal (INE)

---

# 8. Author

**Carolina Ferreira Mateus**  
MSc Information Management - Business Intelligence  
NOVA Information Management School (NOVA IMS)

---

# 9. Supervisor

Prof. Fátima Trindade Neves
