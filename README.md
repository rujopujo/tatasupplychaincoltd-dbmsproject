# Tata Supply Chain Co. Ltd. DBMS Project

This repository contains the core design artifacts for the **Industrial Products Procurement DBMS** project.

## Files in this repository

- `tatasupplychaincoltd-dbmsproject-erdiagram.pdf`
  - ER and relational schema blueprint.
  - Prepared by **Ruhaan Joshi**.
- `tatasupplychaincoltd-dbmsproject-tablestructure.xlsx`
  - Detailed table-wise schema, columns, keys, and descriptions, prepared by **Mrunal Warange**.
## Sample Data for Database Representation
Database Files containing Sample Data by **Mrunal Warange**.

## How this design works

The design models an end-to-end procurement and material flow process:

1. Part master and category data define inventory items.
2. Vendor and vendor-part mapping store approved sourcing options and quoted rates.
3. Purchase and goods receipt (GRR) entities capture incoming material.
4. Quality inspection records accepted and rejected quantities.
5. MIR entities track issue of material to departments.

Together, these entities support procurement planning, receipt tracking, quality control, and stock movement in a normalized relational structure.

## What can be added next

- SQL DDL scripts (`CREATE TABLE`, keys, constraints) for direct database setup.
- Sample test data and query set for validation and demonstration.
- Views/stored procedures for procurement and inspection reports.
- Indexing and performance tuning notes for larger datasets.
- Data dictionary with business rules and allowed values.

## Contributors

- **Ruhaan Joshi** (`ruhaanjoshi2006@gmail.com`)
- **Mrunal Warange** (`mrunal.workonly@gmail.com`)
