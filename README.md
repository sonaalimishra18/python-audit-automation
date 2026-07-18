# Automated Spatial Data Quality Auditor

A Python-based automation tool that audits large-scale municipal land parcel datasets for topological errors and missing attributes, cutting a 3-day manual audit down to under 2 minutes.

## Problem
Manual QA/QC on land parcel datasets was slow and error-prone — a single audit cycle across 10,000+ records took up to 3 days, delaying downstream urban planning decisions.

## Approach
- Built Python scripts to programmatically detect topological errors: overlaps, gaps, and slivers
- Added logic to flag missing or inconsistent attribute data
- Generated automated Data Health Reports (CSV/Excel) for stakeholders, replacing manual spot-checks

## Tools Used
Python, ArcGIS, Excel, GeoPandas

## Outcome
- Reduced a 3-day manual audit process to a 2-minute automated script
- Achieved 100% data integrity validation across 10,000+ municipal land parcel records
- Standardized reporting output for non-technical stakeholders
