# Soly Lagoons Real Estate Performance

An executive analytics experience for Soly Lagoons that brings unit availability, reservations, sales, pricing, customer-facing unit lookup, and management priorities into one decision flow.

The project started with a simple business need: give the team a reliable view of what is sold, what is reserved, what is still available, and where the next commercial action should focus. The final report combines a customer-friendly unit explorer with sales and inventory analysis, then closes with an Arabic executive page that translates the numbers into practical decisions.

## What the solution answers

- Which units are sold, reserved, or available, and where are they located on the masterplan?
- How much value is already sold, held in the reservation pipeline, or still exposed as available inventory?
- Which unit types are carrying the commercial performance, and which ones need a focused sales plan?
- How can management move from a KPI review to a clear weekly action list?

## Dashboard pages

### 1. Soly Lagoons project overview

The opening page establishes the commercial context of the development: North Coast, KM 90, the entry reservation amount, starting price, down-payment amount, and payment horizon. It is intentionally a clean project introduction rather than an operational KPI page, so a decision-maker understands the product before reading the performance views.

![Soly Lagoons project overview](assets/soly-lagoons-overview.png)

**Why it matters:** the page gives the sales and management conversation a shared product context. It helps separate the project's market proposition from the operational measures that follow.

### 2. Unit Explorer

The Unit Explorer replaces manual searching through scattered unit lists with one filtered, visual lookup. Users can filter by unit type and status, read the project totals, and use the masterplan to understand where each unit sits in the development. The page also exposes the fields required for a sales conversation: unit type, land area, building area, price, unit number, completion percentage, and sales order date.

The supplied view shows 28 units in total: 6 sold, 12 reserved, and 10 available. That means 64.3% of the units are already sold or reserved, while 35.7% remain available.

![Unit Explorer](assets/unit-explorer.png)

**Business value:** sales can answer a customer's unit question faster, management can see the remaining stock spatially, and the team has a consistent status vocabulary instead of relying on separate spreadsheets or screenshots.

### 3. Sales & Inventory Analytics

This page is the commercial performance view. It compares sold value, reserved pipeline, available inventory, sell-through, unit mix, and monthly sold-value movement. The unit-type cards make the portfolio mix visible instead of treating all units as one total.

The displayed breakdown is:

| Unit type | Total units | Sold | Reserved | Available | Sell-through | Portfolio value |
|---|---:|---:|---:|---:|---:|---:|
| Studio | 8 | 2 | 4 | 2 | 25.0% | 20.4M EGP |
| 2 Bedrooms | 9 | 2 | 4 | 3 | 22.2% | 39.2M EGP |
| 1 Bedroom | 11 | 2 | 4 | 5 | 18.2% | 36.6M EGP |

The headline cards on this page show 20.76M EGP sold value, a 21.4% sell-through rate, 40.26M EGP in reserved pipeline, and 35.21M EGP in available inventory. The monthly sold-value trend is included to help the team monitor whether sales activity is sustained or concentrated in a few periods.

![Sales and inventory analytics](assets/sales-inventory-analytics.png)

**Decision use:** the reserved pipeline is the immediate conversion lever; the 1 Bedroom segment has the largest exposure with 5 available units and the lowest sell-through in the displayed mix; 2 Bedrooms carry the largest unit-type value; and Studios show the strongest sell-through and pipeline ratio in this view.

### 4. Executive Insights

The final page is written for an Arabic management review. It turns the report into an action brief rather than repeating chart labels. It brings together the main commercial signal, the most important watchouts, and a short list of priorities such as accelerating reserved-to-sold conversion, protecting the value contribution of 2 Bedrooms, and addressing the available 1 Bedroom stock.

![Executive insights](assets/executive-insights.png)

**Decision use:** this page is the bridge between analysis and action. It gives leadership a reason for each priority, the number behind it, and a monitoring direction that can be reviewed in the next sales cycle.

## Key signals from the supplied views

- **Conversion is the clearest near-term lever.** The displayed reserved pipeline is 40.26M EGP versus 20.76M EGP of sold value. Converting a portion of reserved units would move the project forward without relying only on new lead generation.
- **The portfolio is engaged, but not fully secured.** 18 of 28 units are sold or reserved (64.3%), leaving 10 available units to price, market, and follow up deliberately.
- **1 Bedroom needs the most inventory attention.** It contains 11 units, 5 of them available, and has the lowest sell-through shown (18.2%).
- **2 Bedrooms are the main value driver.** Their displayed portfolio value is 39.2M EGP, the largest of the three types; the segment should be protected from unnecessary discounting while its reserved units are converted.
- **Studios currently show the strongest movement.** Their 25.0% sell-through and 75.0% sales-pipeline ratio make them a useful benchmark for message, price, and channel performance.
- **The monthly trend should be used as a cadence check.** A few strong months should not be treated as a stable run rate; the team should monitor sold value and unit conversion weekly.

## Data validation note

The supplied pages do not currently use one perfectly consistent definition for every monetary KPI:

- The Unit Explorer shows **104.7M EGP** total amount, **22.5M EGP** sold, and **38.3M EGP** available.
- The Sales and Executive pages show **96.23M EGP** total project value, **20.76M EGP** sold, and **35.21M EGP** available.

The unit counts and status shares reconcile cleanly (6 sold + 12 reserved + 10 available = 28 units; 21.4% sold and 64.3% sold-or-reserved). The monetary differences should be reconciled in the Power BI model before the figures are used in a formal financial or board report—most likely by standardising the price field, snapshot date, and inclusion rules for the three pages. This repository keeps the screenshots unchanged and documents the discrepancy instead of presenting conflicting totals as if they were one measure.

## Analytical approach

- Defined the business questions before choosing visuals.
- Separated sold, reserved, and available inventory states.
- Combined status counts with monetary pipeline values.
- Used unit-type analysis to connect inventory exposure with commercial priority.
- Added a visual masterplan so unit status can be understood spatially.
- Translated the findings into Arabic executive insights and recommended actions.

## Tools and skills demonstrated

- Microsoft Power BI
- DAX measures and KPI design
- Power Query and data preparation
- Data modeling and relationship design
- Real-estate sales and inventory analysis
- Executive reporting and Arabic data storytelling
- Dashboard UI/UX and decision-focused documentation

## Repository contents

This repository contains the four supplied dashboard screenshots and the written project documentation. The images are kept as provided; no dashboard image was edited. Source data and the Power BI project file are not included in this public documentation repository.

## Author

Mohamed Elantary — Data Analyst

[LinkedIn](https://www.linkedin.com/in/mohamed-elantary-data/) · [GitHub](https://github.com/elantary11)
