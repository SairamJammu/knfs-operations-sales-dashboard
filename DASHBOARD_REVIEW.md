# Dashboard Review Notes

This review summarizes the inspected project assets and the final repository curation.

## Final Project File

The portfolio-ready Power BI file is:

- `dashboard/KNFS_Dashboard.pbix`

This file contains a 10-page KNFS report:

- Final Dashboard
- 1 Q
- 2 Q
- 3 Q
- 4 Q
- 5 Q
- 6 Q
- 7 Q
- 8 Q
- Buyer Insights

The executive dashboard includes KPI cards, product revenue analysis, department sales analysis, reorder alerts, inventory quantity and value analysis, and aging inventory views.

## Files Reviewed

| File | Role | Keep in GitHub |
|---|---|---|
| `dashboard/KNFS_Dashboard.pbix` | Final Power BI dashboard | Yes |
| `Presentation/KNFS_Report.pdf` | Final written/presentation report | Yes |
| `Screenshots/overview-dashboard.png` | Dashboard preview image | Yes |
| `Group 4 Presentation - Draft 1.pptx` | Draft deck with placeholders and blank slides | No |
| `DV Final Project.pbix` | Earlier final-project PBIX version | No |
| `DV Final Project - Copy.pbix` | Working copy with extra draft pages and experiments | No |
| Other root `.pbix`, `.xlsx`, and `.jpg` files | Class exercises or supporting practice files | No |

## Professional Polish Assessment

The dashboard is already framed around real operating decisions:

- Sales performance
- Department performance
- Inventory exposure
- Reorder prioritization
- Aging inventory
- Margin performance

The main repo-level issue was presentation discipline. The repository previously included class exercises and draft files that distracted from the final KNFS dashboard. Those have been removed from the GitHub-ready version.

## Recommended PBIX Edits in Power BI Desktop

Some improvements require Power BI Desktop because direct binary PBIX editing can corrupt the file. Recommended next edits:

- Rename report tabs from question labels to business labels.
- Use title case consistently across all visual titles.
- Replace classroom phrasing with operator-facing labels.
- Tighten visual spacing and align all objects to a grid.
- Reduce heavy shadows and oversized rounded corners.
- Add a report subtitle with the data period and refresh date.
- Review filters so each page has one clear user action.

## Suggested Page Names

| Current Page | Suggested Page Name |
|---|---|
| `Final Dashboard` | `Executive Overview` |
| `1 Q` | `Top Products` |
| `2 Q` | `Sales Underperformers` |
| `3 Q` | `Inventory Value` |
| `4 Q` | `Reorder Priorities` |
| `5 Q` | `Aging Inventory` |
| `6 Q` | `Sales and COGS` |
| `7 Q` | `Department Sales` |
| `8 Q` | `Margin Summary` |
| `Buyer Insights` | `Buyer Insights` |
