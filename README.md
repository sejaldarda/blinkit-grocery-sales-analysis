# Blinkit Grocery Sales Analysis | Power BI

An interactive Power BI dashboard designed to explore grocery sales performance across product categories and outlet characteristics. The report helps users compare sales patterns and identify areas that may warrant further business investigation.

## Dashboard Preview

Add your screenshot to `images/blinkit-dashboard.png`, then uncomment the line below:

<!-- ![Blinkit Grocery Sales Dashboard](images/blinkit-dashboard.png) -->

> **Preview tip:** Add a clear screenshot of the dashboard above so visitors can understand the report before downloading the Power BI file.

## Project Objectives

- Analyze overall grocery sales performance.
- Compare sales across item categories.
- Explore differences between outlet types and outlet sizes.
- Examine sales patterns by product fat content and outlet establishment year.
- Present key metrics and comparisons in an interactive report.

## Tools and Skills

- **Power BI Desktop** — dashboard development and data visualization
- **Power Query** — data preparation and transformation, where used
- **DAX** — measures and calculated fields, where used
- **Data analysis** — KPI analysis, category comparisons, and trend exploration

*Keep only the tools and techniques you personally used in the final version.*

## Dashboard Contents

Document the visuals included in your actual report. Common analysis areas for this type of dashboard include:

- **KPI cards:** total sales, average sales, number of items, and average rating (if present in your report)
- **Item category analysis:** comparison of sales by product category
- **Outlet analysis:** sales comparisons by outlet type and outlet size
- **Product mix:** comparison of Low Fat and Regular items
- **Establishment-year analysis:** sales distribution by outlet establishment year

## Business Insights

Use the actual values shown by your report to complete these findings. Replace every bracketed field before publishing; do not leave these prompts as if they were verified results.

1. **Leading item category:** `[Category]` generated `₹[value]`, representing `[percentage]%` of total sales. This helps identify the categories that contribute most to revenue.
2. **Outlet-type comparison:** `[Outlet type A]` generated `₹[value]` compared with `₹[value]` for `[Outlet type B]`. This highlights differences in revenue across store formats.
3. **Outlet-size comparison:** `[Outlet size]` recorded `₹[value]` in sales, compared with `₹[value]` for `[other size]`. This helps assess how outlet size relates to sales in this dataset.
4. **Product fat-content mix:** `[Low Fat/Regular]` products accounted for `[percentage]%` of sales, compared with `[percentage]%` for the other group. This describes the sales mix by fat content.
5. **Outlet establishment trend:** Outlets established in `[year/period]` recorded `₹[value]` in sales, compared with `₹[value]` for `[comparison year/period]`. This highlights a pattern across outlet establishment cohorts.

**Validation:** Confirm the numbers, units, filters, and denominator in Power BI before using these statements. If your dashboard does not contain a visual for a finding, remove that finding or add the appropriate analysis first.

## Dataset

- **Dataset file:** Add the original CSV/XLSX used by the Power BI report to the `data/` folder.
- **Suggested path:** `data/blinkit_grocery_data.csv` (change this to match your real filename and file type).
- **Source:** `[Insert the original dataset source URL]`
- **Attribution/license:** `[Add the dataset creator, license, and any required attribution]`

Do not include a different dataset simply because it has a similar name. The data should match the file used to build the dashboard. If redistribution is not permitted, provide the source link and instructions instead of uploading the data.

## Repository Structure

```text
blinkit-grocery-sales-analysis/
├── README.md
├── dashboard/
│   └── Blinkit-analysis.pbix
├── data/
│   └── [original-dataset-file]
└── images/
    └── blinkit-dashboard.png
```

## How to View the Dashboard

1. Download or clone this repository.
2. Open `dashboard/Blinkit-analysis.pbix` using Power BI Desktop.
3. If Power BI asks for the dataset location, update the source path to the file in `data/`.
4. Refresh the data if required.
5. Explore the report visuals and available filters.

Power BI Desktop is required to open and interact with the `.pbix` file. A screenshot can be viewed without Power BI.

## Limitations and Notes

- Results depend on the dataset, data cleaning, and filters applied in the report.
- Correlation or differences in the visuals should not automatically be interpreted as causation.
- Numerical business insights should be checked against the final dashboard before publication.

## Author

**[Your Name]**

- GitHub: [Your GitHub profile URL]
- LinkedIn: [Your LinkedIn profile URL]

---

*This project is part of my Data Analytics portfolio.*
