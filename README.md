# Vrinda Store Annual Sales Analysis (2025)

A hands-on data analytics project built using Microsoft Excel. The goal of this project was to analyze Vrinda Store’s 2025 sales data to spot key customer trends, see which sales channels perform best, and figure out actionable ways to grow revenue in 2025.

---

# Project Overview

Vrinda Store wanted a simple, visual way to make sense of their yearly sales data. I took their raw order spreadsheet, cleaned up the messier columns, built out custom calculations, and put together an interactive Excel dashboard with dynamic charts and slicers.

# Key Questions Answered:
- Which month saw the highest sales volume and order numbers?
- Who spends more—men or women?
- Which demographic (age + gender) is our core customer base?
- What are the top 5 states bringing in the most revenue?
- How much revenue comes from third-party platforms like Amazon, Flipkart, and Myntra?

---

# What I Did (Data Cleaning & Processing)

Before building any charts, the raw dataset needed a bit of cleanup:
- *Fixed Gender Labels:* Standardized mixed inputs (like M, W, Men, Women) into uniform Men and Women labels.
- *Created Age Buckets:* Added an Age Group column using nested logic to classify buyers into Senior (50+), Adult (30–49), and Teenager (<30).
- *Extracted Months:* Used TEXT(date, "mmm") to pull out 3-letter month abbreviations from order dates.
- *Number Formatting:* Cleaned up large revenue numbers into easily readable formatting.

---

## 📊 Dashboard & Visuals

The interactive dashboard includes:
- *Sales vs. Orders Trend:* A combined dual-axis line/column chart tracking revenue against order count month by month.
- *Demographics Breakdown:* Visuals showing sales spread across gender and age brackets.
- *Top 5 States:* Horizontal bar chart highlighting revenue share across key regional markets.
- *Channel Share:* Breakdown of sales coming from Amazon, Flipkart, Myntra, and direct channels.
- *Dynamic Slicers:* Interactive filters that let you inspect the whole dashboard by Month, Sales Channel, or Product Category.

---

# Key Takeaways & Recommendations

- *Top Demographic:* Women make up about 65% of all orders, with Adult Women (ages 30–49) being the single biggest buyer group (~35% of total revenue).
- *Peak Season:* March brought in the highest sales and order volume across the entire year.
- *Primary Channels:* Amazon (~35%), Flipkart, and Myntra drive over 80% of total sales.
- *Top Regions:* Maharashtra, Karnataka, and Uttar Pradesh top the list for total sales volume.

*Bottom Line Strategy:* To boost sales next year, Vrinda Store should focus marketing campaigns and promotional discount codes specifically toward Adult Women in Maharashtra, Karnataka, and UP, running ads primarily on Amazon, Flipkart, and Myntra ahead of spring peak buying periods.

---

# How to Run This Project

1. Download or clone this repository.
2. Open the .xlsx file in Microsoft Excel 2016 or newer.
3. Head over to the Vrinda Store Report tab to view the dashboard.
4. Click around the Slicers on the left side to filter data across different months, channels, and product lines.

