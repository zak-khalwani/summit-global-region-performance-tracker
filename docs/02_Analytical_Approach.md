# 2. The Analytical Approach

This document explains the methodology behind the Regional Performance Tracker. The dashboard's design is centered on providing constant context, ensuring no number is ever viewed in isolation. This is achieved through a "Trifecta" analysis framework: **Actuals vs. Target vs. Historical**.

## The Target-Setting Methodology

The sales targets are not arbitrary numbers but are calculated with a clear, consistent logic:
**`2017 Target = 2016 Actual Sales * 1.05`**

This means the goal for the current year is defined as a 5% growth over the previous year's performance. This logic is applied at the regional (country) level.

## The Daily Target Allocation

A key feature of the dashboard is the ability to track performance against a target on a daily basis. This is achieved through a **Daily Target Allocation** logic.

The full annual target for a region is divided by the number of days in the year and then spread evenly across each day. This provides a consistent linear target line, which is crucial for the `Daily Performance` chart and the `Performance vs Target` cumulative chart. It allows managers to track if they are "on pace" to hit their goal at any point in the year.

## The Analytical Workflow

The dashboard guides the user through a logical analysis of performance:

1.  **High-Level Summary:** The main KPI card provides the three most critical metrics in one place: the absolute sales number, its performance vs. target, and its performance vs. last year. This is the starting point for any analysis.

2.  **Cumulative Trend Analysis:** The three area charts are designed to tell a story over time:
    *   `Performance vs Target` shows the "race against the goal."
    *   `Performance vs Target Different` quantifies the exact dollar amount of the gap, making it tangible.
    *   `Current vs Last Year Performance` provides a sanity check, showing growth relative to the past.

3.  **Granular Diagnosis:** The interactive map allows a user to select a region of interest. Once a region is selected, the `Store Performance` table provides the next layer of detail, showing which specific cities are the top or bottom performers within that region, enabling focused managerial intervention.