# Fast Food Calories Dashboard

An interactive dashboard for exploring fast-food calorie trends alongside consumer characteristics such as age, weight, sugar weight, activity level, and workout-shock tier.

![Fast Food Calories Dashboard](dashboard.png)

## Overview

This dashboard brings together key metrics and visualizations to make it easier to compare fast-food chains and meal categories. It highlights calorie-related patterns and provides a snapshot of several consumer and order-related measures.

## Dashboard Highlights

### Key Metrics
- **Average daily calories:** 80.13
- **Total items count:** 28K
- **Average consumer weight:** 77.80
- **Average sugar weight:** 62.25

*These values are shown as displayed in the dashboard; their units and calculation definitions should be documented alongside the source data.*

### Visualizations
- **Items by fast-food chain:** Donut chart showing each chain's share of the item count.
- **Fast-food chains by calories:** Horizontal bar chart comparing calorie totals across chains.
- **Consumer age by calories:** Line chart showing how the displayed calorie measure varies by age.
- **Meal by total calories:** Horizontal bar chart comparing total calories across meal categories.
- **Calories surplus by age:** Line chart showing the displayed calorie-surplus measure across ages.
- **Order count by workout-shock tier:** Pie chart showing the distribution of orders across workout-shock tiers.
- **Fitness-level filters:** Dashboard controls for Highly Trained, Moderately Active, and Sedentary groups.

## How to Use

1. Open the dashboard in its original BI tool or published format.
2. Use the fitness-level controls to filter the dashboard, if interactivity is enabled.
3. Compare the chain and meal charts to see which categories contribute the largest displayed calorie totals.
4. Review the age-based charts to explore how the displayed measures vary across age groups.
5. Use the item-count and workout-shock visuals to inspect the distribution of items and orders.

## Main Insights Visible in the Screenshot

- McDonald's has the largest displayed calorie total among the fast-food chains shown.
- The meal categories have relatively similar displayed totals, with Loaded Burrito, Nachos & Soda appearing highest in the chart.
- The consumer-age calorie line fluctuates across the displayed age range rather than following a steady upward or downward trend.
- The workout-shock-tier chart shows Extreme as the largest displayed segment, followed by Severe Cardio and High Sweat.

These are visual observations from the screenshot, not conclusions about health outcomes or causal relationships.

## Data and Definitions

The screenshot does not include the underlying dataset, source links, or metric definitions. Before publishing the repository, consider documenting:

- Dataset name and source URL or file
- Meaning and units of each calorie, weight, and sugar metric
- Whether calorie figures are averages, sums, or another aggregation
- Definitions for *workout-shock tier* and *fitness level*
- Data cleaning steps and any assumptions made

## Tools / Technology

The screenshot appears to show a BI dashboard. Add the exact tool and version used to build it (for example, Power BI or Tableau), along with any data-preparation tools or languages used.

## Repository Contents

Suggested repository structure:

```text
fast-food-calories-dashboard/
├── README.md
├── dashboard.png
├── data/                  # Add source data if you are allowed to share it
└── project-files/          # Add the original dashboard/project file
```

## How to View

This repository README displays a screenshot preview. To explore filters and interactions, include the original dashboard file or a published dashboard link in the repository.

## Limitations

- The README is based on the provided dashboard screenshot.
- The dataset, metric formulas, units, and dashboard software were not provided, so they are intentionally not assumed.
- The dashboard shows descriptive patterns; it does not establish that a particular food or consumer characteristic causes a health outcome.

## Author

**Your Name**  
BBA – Business Analytics  
[GitHub Profile](https://github.com/your-username)

---

If you use or adapt this dashboard, please cite the original dataset and any external sources used.
