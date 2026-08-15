# Airbnb Investment Analysis Project

## Overview
This project provides a comprehensive data-driven analysis designed for real estate investors looking to launch a profitable Airbnb business. Using detailed listings and calendar data, this Tableau project helps identify the best locations to purchase a property, optimal pricing strategies, and key structural factors to maximize return on investment (ROI).

---

## Investor Use Case & Objectives
When starting an Airbnb business, an investor needs to answer critical strategic questions:
* **Where is the best place to buy?** Identify top-performing neighborhoods and cities based on demand and revenue potential.
* **What property specifications drive profit?** Determine the ideal number of bedrooms, bathrooms, and property types.
* **How much can I charge?** Analyze competitive pricing dynamics, seasonal fluctuations, and nightly rates.
* **What factors impact profitability?** Evaluate cleaning fees, minimum stay requirements, host performance metrics, and occupancy rates.

---

## Dataset Structure & Integration
The project integrates two core data files via an inner join on listing identifiers:
* **Listings Data:** Contains detailed metadata including host info, geographic coordinates (`latitude`, `longitude`), neighborhood classifications, room types, property types, and amenities.
* **Calendar Data:** Contains rolling availability, booking status, and pricing mapped across specific dates for each listing.

---

## Key Factors & Metrics Considered
* **Location & Geography:** Neighborhood-level performance tracking to pinpoint high-demand areas.
* **Property Configurations:** Analysis of room types, capacity (`accommodates`), and bedroom counts to target high-yield configurations.
* **Pricing Strategy:** Standard nightly rates, cleaning fees, security deposits, and weekly/monthly discounts.
* **Availability & Occupancy:** Tracking availability windows (30, 60, 90, and 365 days) to estimate annual utilization.
* **Reviews & Guest Satisfaction:** Review scores across cleanliness, communication, and location that directly influence booking frequency.

---

## Repository Contents
* **`Tableau Full Project.twbx` / Workbook Files:** The complete Tableau dashboard file containing data connections, calculated fields, and interactive visualizations.
* **Data Sources:** Source Excel files (`Tableau Full Project.xlsx`) containing raw listing and calendar data.

---

## Getting Started & Usage
1. Clone or download this repository.
2. Open **Tableau Desktop** (compatible with version 18.1 / 2026.2 or later).
3. Open the workbook file to interact with the investment dashboard, filter by neighborhood or bedroom count, and evaluate revenue potential.
