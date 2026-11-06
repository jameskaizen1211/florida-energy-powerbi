# Florida Energy — Power BI Portfolio Project

**Author:** James Booth II ([jameskaizen1211](https://github.com/jameskaizen1211))  
**Stack:** SQL Server · Power BI Desktop · Power BI Report Builder  
**Theme:** Custom navy/teal (`Eclipse_NavyTeal_Portfolio.json`)

End-to-end BI sample that mirrors a common enterprise pattern: load source data into SQL Server, build a Power BI semantic model on top, then publish interactive and paginated reports from that model.

---

## Overview

This project demonstrates a SQL → semantic model → report pipeline:

1. **SQL Server** local database `FloridaEnergy` with table `dbo.Generators`
2. **Power BI Desktop** semantic model and interactive report (`Florida_Energy_Project.pbix`)
3. **Power BI Report Builder** paginated report connected to the published semantic model (not directly to SQL)

Designed as portfolio evidence for a Power BI Business Intelligence Analyst & Developer role.

---

## Tools

| Tool | Role |
|------|------|
| SQL Server (local) | Source database `FloridaEnergy` |
| SSMS | Database management |
| Power BI Desktop | Semantic model + interactive report |
| Power BI Report Builder | Paginated report against the semantic model |
| Custom theme JSON | Consistent navy/teal branding |

---

## Data Model

- **Database:** `FloridaEnergy` (local SQL Server)
- **Primary table:** `dbo.Generators`
- **Semantic model:** Built in `Florida_Energy_Project.pbix` and used as the shared source for Report Builder

> **TODO:** Add star-schema diagram, relationship list, and key measures once documented.

---

## Report Highlights

- Interactive Power BI report with custom navy (#1B2A41) / teal (#0FA3B1) theme
- Paginated Report Builder output bound to the Power BI semantic model
- Recruiter-friendly layout: KPI row, clear titles, consistent alignment (see theme + touch-up checklist)

> **TODO:** List specific pages, visuals, and DAX measures after final polish.

---

## How to Open

### Prerequisites
- Power BI Desktop (current version)
- Access to a SQL Server instance with the `FloridaEnergy` database restored *(TODO: add backup / script link)*
- Power BI Report Builder (for the paginated report)
- Optional: import `Eclipse_NavyTeal_Portfolio.json` via **View → Themes → Browse for themes**

### Steps
1. Restore or create the `FloridaEnergy` database and confirm `dbo.Generators` is available.
2. Open `Florida_Energy_Project.pbix` in Power BI Desktop.
3. Update the SQL data source credentials if prompted, then **Refresh**.
4. Open the Report Builder (`.rdl`) file and point it at the published semantic model named after `Florida_Energy_Project`.
5. Apply the custom theme JSON if visuals need re-theming after refresh.

> **TODO:** Add exact `.rdl` filename and publish/workspace steps once finalized.

---

## Screenshots

<!-- Replace placeholders after applying the navy/teal theme and exporting PNGs -->

| View | Image |
|------|--------|
| Report overview | ![Overview](screenshots/overview.png) <!-- TODO --> |
| KPI / summary page | ![KPIs](screenshots/kpis.png) <!-- TODO --> |
| Detail / generator view | ![Detail](screenshots/detail.png) <!-- TODO --> |
| Paginated report | ![Paginated](screenshots/paginated.png) <!-- TODO --> |

---

## Skills Shown

- SQL Server source modeling (`FloridaEnergy` / `dbo.Generators`)
- Power BI semantic model design
- Interactive report design with custom theme
- Power BI Report Builder (paginated reports from a semantic model)
- End-to-end BI pipeline thinking (database → model → reports)

---

## Repository Contents

```
florida-energy-powerbi/
├── README.md
├── Florida_Energy_Project.pbix          # TODO: add when ready to publish
├── Eclipse_NavyTeal_Portfolio.json      # Custom report theme
├── screenshots/                         # TODO: add PNGs
└── sql/                                 # TODO: schema / seed scripts
```

---

## About the Author

James Booth II — SNHU MBA candidate building a Power BI portfolio for BI Analyst & Developer roles.  
GitHub: [jameskaizen1211](https://github.com/jameskaizen1211)
