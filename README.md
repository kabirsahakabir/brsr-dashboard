# OSH BRSR Data Health Dashboard

A browser-based tool for Client Success Managers at **Oren Sustainability Hub** to analyse BRSR data quality from the OSH portal.

## How to use

1. Open the dashboard URL
2. Drag and drop any client's **OSH portal Details export** (`.xlsx` file)
3. The dashboard runs entirely in your browser — no data is uploaded anywhere

## What it checks

- **Missing data** — months with no submission
- **Month-on-Month anomalies** — unusual spikes or drops vs the previous month (with smart unit conversion)
- **Statistical anomalies** — IQR fencing + Z-score outliers vs the full-year average
- **Unit inconsistencies** — mixed units across months for the same metric
- **Zero values** — submitted as 0, may need verification
- **Consecutive gaps** — 3+ months with no data
- **Annual YoY deviation** — annual totals that changed significantly vs last year

## Metrics tracked (12)

Electricity, Renewable Energy, Non-Renewable Combustion, Mobile Combustion,
Water Consumption, Water Discharge, Waste Generated, Fugitive Emissions,
Purchased Heat & Electricity, Safety Incidents, Permanent Employees, Employee Wages

## Pages (11)

Overview · BU Scorecards · Data Heatmap · Monthly Trends · Issues Log ·
Anomaly Drill-Down · Data Inspector · Action Center · BU Comparison ·
Issue Tracker · Client Report Generator

## Privacy

All processing happens entirely in your browser. The Excel file is never uploaded
to any server. Issue tracking notes are saved only in your browser's local storage.

---

Built by Oren Sustainability Hub — Internal Tool
