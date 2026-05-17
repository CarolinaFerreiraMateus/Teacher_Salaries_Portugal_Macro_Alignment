# 02_Staging – Data Preparation and Validation

This folder documents the staging and data preparation layer used in the project.

The staging layer was conceptually designed to support the integration, validation and preparation of educational salary data and macroeconomic indicators before loading them into the dimensional data warehouse.

---

## Purpose

The staging layer supports:
- Initial integration of heterogeneous data sources
- Data cleaning and normalization
- Alignment between academic years and calendar years
- Preparation of analytical structures for dimensional modeling
- Validation of data consistency before warehouse loading

---

## Main transformations

### Salary data
- Standardization of salary categories and career stages
- Alignment of academic-year salary data with calendar years
- Harmonization of ISCED levels, roles and salary stages
- Verification of missing or inconsistent values

### Macroeconomic indicators
- Standardization of indicator names, formats and units
- Validation of annual temporal coverage
- Alignment of macroeconomic indicators with salary datasets
- Preparation of indicators for comparative analysis

---

## Validation procedures

Validation procedures included:
- Business key consistency checks
- Referential integrity validation
- Temporal alignment verification
- Data quality inspection before loading into the data warehouse

---

## Relation to thesis

This folder corresponds to the data preparation, staging and validation procedures described in Chapter 3 of the dissertation.
