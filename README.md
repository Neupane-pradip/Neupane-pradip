<h1 align="center">Pradip Neupane</h1>
<p align="center"><strong>Building data pipelines that turn APIs into useful analytics</strong></p>
<p align="center">MSc Data Science student · Python & SQL · Data engineering portfolio</p>
<p align="center">
  <a href="https://github.com/Neupane-pradip/weather-data-pipeline">Weather Pipeline</a> ·
  <a href="https://github.com/Neupane-pradip/fpl-analytics-elt">FPL Analytics</a> ·
  <a href="mailto:pradip.neupane@tuni.fi">Contact</a>
</p>

---

## About me

I'm a Data Science master's student with a background in software development and mathematics, building toward a career in data engineering.

I learn by building complete projects: extracting data from APIs, designing SQL tables, validating records, handling failures, and making the results useful through analytics. My repositories document both the implementation and what I learn along the way.

## Featured projects

### Weather Data Pipeline
**Python · PostgreSQL · Pandas · Streamlit**

A scheduled ETL pipeline that collects weather for Helsinki, London, and Berlin and displays stored observations in a dashboard.

- **Collection:** multi-city batches scheduled every 15 minutes with Windows Task Scheduler.
- **Data quality:** missing-temperature validation, UTC timestamps, and database constraints that prevent duplicate observations.
- **Reliability:** bounded API retries, per-city error handling, execution logs, and a local test for recovery from a temporary server failure.
- **Analytics:** latest saved temperatures, historical trends, and a refreshable records table in Streamlit.

```text
Open-Meteo API → Python extraction & validation → PostgreSQL → Streamlit
                            ↑
                   Windows Task Scheduler
```

[Explore the code and setup instructions →](https://github.com/Neupane-pradip/weather-data-pipeline)

### FPL Analytics ELT
**Python · DuckDB · Pandas · SQL**

A Fantasy Premier League data project that stages API data and transforms it into an analytics model.

- SQL transformations build player, team, and gameweek dimensions plus a player-statistics fact table.
- Data quality checks cover uniqueness, missing values, orphaned team references, and invalid numeric ranges.
- Separate extraction, loading, transformation, and validation modules organize the pipeline.

[Explore the data model and pipeline →](https://github.com/Neupane-pradip/fpl-analytics-elt)

### Titanic Survival Prediction
**Python · Pandas · scikit-learn**

A machine learning project covering preprocessing, model comparison, evaluation, and visualizations.

[Explore the project →](https://github.com/Neupane-pradip/-Titanic-Survival-Prediction)

## Skills demonstrated in my projects

| Area | Tools and practices |
|---|---|
| Programming | Python, SQL |
| Data pipelines | API extraction, ETL/ELT, batch processing, scheduled collection |
| Storage & modeling | PostgreSQL, DuckDB, SQL schemas, dimensional modeling |
| Reliability | Validation, duplicate prevention, logging, exception handling, API retries |
| Analytics | Pandas, Streamlit |
| Development | Git, GitHub, virtual environments, environment-based configuration, automated testing |

## What I'm learning next

- Historical backfills and incremental loading
- Broader automated tests and continuous integration
- Reproducible environments and deployment

## Education

**MSc in Data Science** — in progress · Expected graduation: December 2027

**BSc in Computing Science and Electrical Engineering** — completed  
Major: Software Development · Minor: Mathematics

## Connect

Interested in discussing data pipelines, project feedback, or early-career data engineering opportunities?

[Email me](mailto:pradip.neupane@tuni.fi)
