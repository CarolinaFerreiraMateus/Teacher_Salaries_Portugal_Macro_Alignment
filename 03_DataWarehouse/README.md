# 03_DataWarehouse – Dimensional Model and Warehouse Loading

This folder documents the dimensional data warehouse developed for the dissertation project.

The warehouse integrates educational salary data and macroeconomic indicators through a Kimball-based dimensional modeling approach implemented in Microsoft Fabric.

---

## Dimensional modeling approach

The data warehouse was designed following Kimball dimensional modeling principles, using a star-schema structure composed of fact and dimension tables.

The model supports:
- Longitudinal salary analysis
- Macroeconomic indicator integration
- Cross-dimensional comparisons
- Analytical consistency across educational and economic datasets

---

## Fact tables

### Fact_Salary
Stores salary measures for teachers and school heads across:
- Career stages
- Roles
- ISCED levels
- Qualification levels
- School sizes
- Years and countries

### Fact_Macro
Stores macroeconomic indicators such as:
- GDP per capita
- Consumer Price Index
- Average annual wages
- Education expenditure
- Purchasing Power Parity
- Housing-related indicators

---

## Dimension tables

The warehouse includes conformed dimensions such as:
- Dim_Year
- Dim_Country
- Dim_Isced
- Dim_Role
- Dim_Qualification
- Dim_Salary_Stage
- Dim_Currency
- Dim_Indicator
- Dim_School_Size

---

## Warehouse loading process

The warehouse loading process included:
- Dimension loading and surrogate key generation
- Fact table loading after dimension validation
- Referential integrity verification
- Sequential orchestration of dimension and fact loading procedures

---

## Relation to thesis

This folder corresponds to the dimensional modeling and warehouse loading procedures described in Chapter 3 of the dissertation.
