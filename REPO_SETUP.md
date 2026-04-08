# Repository Setup and Migration Plan

This workspace now includes local scaffold folders for the six repositories you requested:

1. `kagnaem` (profile README repo; this current repo)
2. `data-analytics-portfolio`
3. `data-pipeline-projects`
4. `azure-fabric-analytics`
5. `google-data-analytics`
6. `powerbi-analytics-projects`
7. `excel-analytics-projects`

## Scaffold location

All new repository scaffolds are under `./scaffolds/`.

## Standard structure created

Each scaffold includes:

- `projects/` for project folders
- `templates/` for reusable README templates
- `assets/` for screenshots and images

And `data-analytics-portfolio` also includes:

- `CV/` for your resume PDF

## Project placement guide

Use this mapping when moving project files:

- Data pipeline / ETL / orchestration -> `data-pipeline-projects/projects/<project-name>/`
- Azure + Fabric projects -> `azure-fabric-analytics/projects/<project-name>/`
- BigQuery / Looker Studio / Google analytics -> `google-data-analytics/projects/<project-name>/`
- Power BI reports and dashboards -> `powerbi-analytics-projects/projects/<project-name>/`
- Excel analysis / KPI models / advanced formulas -> `excel-analytics-projects/projects/<project-name>/`

## Notes

- This environment can scaffold folders and files locally but cannot directly create GitHub repos via `gh` because GitHub CLI is not installed.
- After you create repos on GitHub, copy each scaffold folder into its corresponding local git repo, commit, and push.
