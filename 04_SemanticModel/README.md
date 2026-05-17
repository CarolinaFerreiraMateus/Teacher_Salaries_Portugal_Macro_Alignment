# 04_SemanticModel – Analytical and Semantic Layer

This folder documents the semantic model that supports the Power BI dashboard developed in the dissertation project.

The semantic layer was developed on top of the dimensional data warehouse implemented in Microsoft Fabric and enables analytical querying, filtering and visualization across educational salary data and macroeconomic indicators.

---

## Semantic model design

The semantic model follows a star-schema structure, where fact tables are connected to shared dimensions through one-to-many relationships.

This structure supports:
- Consistent analytical navigation
- Cross-indicator comparison
- Longitudinal salary analysis
- Interactive filtering across dimensions
- Integration between educational and macroeconomic datasets

---

## Main analytical components

### Fact tables
- Fact_Salary
- Fact_Macro

### Shared dimensions
- Dim_Year
- Dim_Country
- Dim_Isced
- Dim_Role
- Dim_Qualification
- Dim_Salary_Stage
- Dim_Indicator
- Dim_Currency

---

## Analytical capabilities

The semantic layer supports:
- Nominal vs real salary analysis
- Inflation-adjusted salary comparison
- Salary evolution relative to GDP and wages
- Cost-of-living and housing affordability analysis
- European comparative analysis using PPS-adjusted salaries

---

## Measures and calculations

The semantic model includes analytical measures developed in Power BI using DAX, supporting:
- Aggregation of salary values
- Comparative indicator analysis
- Year-over-year comparisons
- Percentage growth calculations
- Ratio and index analysis

---

## Relation to thesis

This folder corresponds to the semantic modeling and analytical layer described in Chapter 3 of the dissertation.
