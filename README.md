# Kenyan Agri-Exports Executive Dashboard

A Power BI dashboard I built to track Kenya's agricultural export revenue, where it's going, and how the sales team is doing.

---

## Dashboard Preview
![Kenyan Agri-Exports Executive Dashboard](Kenya%20Agri%20Exports%20Power%20Bi%20Dashboard%20snipet.png)

---

## What This Is
I wanted to pull Kenyan agri-export sales data into one dashboard that an executive could open and understand in a few seconds. It shows which products earn the most, which countries buy the most, and how each sales rep is performing, without a lot of visual noise.

---

## Design Choices
I kept the design minimal so the numbers do the talking.

- **Layout:** Card containers group related visuals so the page stays tidy.
- **Colors:**
  * Highland Green (#1B4D3E) for key metrics and top revenue drivers
  * Muted Sage (#D3DEDC) for secondary elements and card backgrounds
  * Deep Slate (#2C3E50) for headers and titles
- **Conditional formatting:** Products earning 1M KES or more are highlighted, so the best performers stand out right away.
- **Number formatting:** Figures are shown in thousands (K), and I dropped unneeded chart axes so the data labels take center stage.

---

## What's on the Dashboard
1. **Monthly revenue trend:** a line chart with no axes, showing how revenue moves over time.
2. **Revenue by country:** a clean pie chart showing each destination market's share of exports.
3. **Sales rep leaderboard:** a sorted table with small in-cell bars and roomy row spacing so it's easy to read.
4. **Product performance:** a horizontal bar chart ranking products by revenue, with color highlighting for the top earners.
5. **Date filter:** a range slider for narrowing the data to a specific period.

---

## Tools
- **Power BI Desktop** for the layout, DAX measures, and visual formatting
- **Power Query** for cleaning and shaping the raw data
- **Data modeling** to connect the dates, products, and sales tables
