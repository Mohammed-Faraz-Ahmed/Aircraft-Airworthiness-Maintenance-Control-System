# Aircraft Airworthiness & Maintenance Control System

An Excel-based aircraft airworthiness and maintenance control system designed to consolidate aircraft records, airworthiness directives, defects, AMP tasks, life-limited parts, risk assessment, and maintenance planning into a dynamic control dashboard.

## Overview

This project demonstrates how Microsoft Excel can be used to build an integrated aircraft maintenance monitoring system rather than a collection of disconnected spreadsheets.

The workbook uses a central aircraft selector to dynamically update aircraft-specific information across multiple maintenance and airworthiness views.
## Screenshots

### Airworthiness Dashboard

![Airworthiness Dashboard](screenshots/dashboard.png)

### Maintenance Planning

![Maintenance Planning](screenshots/maintenance-planning.png)

### Attention Required

![Attention Required](screenshots/attention-required.png)

### Risk & Priority

![Risk & Priority](screenshots/risk-priority.png)

### Maintenance Packaging

![Maintenance Packaging](screenshots/maintenance-packaging.png)

## Key Features

- Dynamic aircraft selection
- Aircraft fleet information
- Airworthiness Directive (AD) tracking
- AD compliance and due-date monitoring
- Defect and MEL category tracking
- AMP task monitoring
- Life-limited part monitoring
- Risk scoring and priority classification
- Attention-required monitoring
- Aircraft technical-log history
- Maintenance planning
- Maintenance packaging
- Dynamic maintenance dashboard
- Conditional formatting for maintenance priorities
- Automated cross-sheet calculations

## Workbook Architecture

The workbook is structured into several functional layers:

### Data Sources

- Aircraft Information
- AD Status
- AMP
- CRS
- Technical Log
- Life Limited Parts

### Analysis & Risk

- Risk Priority
- Risk AMP
- Risk Defects
- Risk & Priority

### Maintenance Control

- Attention Required
- Maintenance Planning
- Maintenance Packaging
- Aircraft History

### Dashboard

The Dashboard provides a consolidated aircraft-level view of:

- Aircraft information
- Open ADs
- Overdue ADs
- Deferred defects
- Life-limited parts approaching limits
- AMP tasks due
- Maintenance planning priorities

Selecting a different aircraft automatically updates the relevant workbook views.

## Example Workflow

1. Select an aircraft from the Dashboard.
2. Review the aircraft's current information and status.
3. Review outstanding ADs and compliance requirements.
4. Check defects and AMP tasks requiring attention.
5. Review risk and priority information.
6. Review the maintenance planning schedule.
7. Review maintenance packages generated from applicable tasks.

## Technical Skills Demonstrated

This project demonstrates practical use of:

- Microsoft Excel
- Dynamic array formulas
- `FILTER`
- `XLOOKUP`
- `COUNTIFS`
- `LET`
- `CHOOSECOLS`
- Data Validation
- Conditional Formatting
- Cross-sheet data integration
- Automated maintenance-status logic
- Dashboard design
- Maintenance planning logic
- Risk-based prioritization

## Purpose

The purpose of this project is to demonstrate practical understanding of aircraft maintenance and airworthiness workflows while applying spreadsheet automation and data-management techniques to create a functional maintenance-control system.

This project was developed as an academic and portfolio project to demonstrate skills relevant to aircraft maintenance, airworthiness, MRO, and aviation engineering environments.

## Disclaimer

This is a student-developed demonstration project using fictional/sample aircraft maintenance data.

It is not intended for operational aircraft maintenance, regulatory compliance, or use as an approved aviation maintenance-control system.

## Author

**Mohammed Faraz Ahmed**

Aerospace/Aeronautical Engineering Student
