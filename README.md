# Zhen Fang

I turn messy operational data into reusable data products people can trust: pipelines, models, tests, and product-facing analytics.

**Python · SQL · dbt · PostgreSQL · FastAPI · Docker · GitHub Actions**

## Featured Work

### [NYC Open Data Activity Pipeline](https://github.com/zhen01/nyc-open-data-pipeline)

End-to-end analytics engineering project: live NYC Open Data ingestion, Postgres, dbt models, FastAPI, React, CI, and scheduled refresh.

What it shows:

- Modeled a messy public feed into staging, intermediate, and mart layers.
- Added dbt tests for product-critical rules: cancelled events, expired events, missing URLs, stale source data, and unknown prices.
- Built SCD2 snapshot and append-only observation tables to preserve source-history signals that the API does not provide.
- Fixed NYC-local timezone correctness in models and tests.

### [Portfolio](https://zhen01.vercel.app/)

Recruiter-facing project and background site.

## Current Direction

I am focused on Analytics Engineering, Data Engineering, Data Platform, and AI/data tooling roles where reliability matters as much as the analysis itself.

The work I am most interested in sits at the point where:

- data quality affects real decisions,
- source systems are messy or incomplete,
- pipelines need clear failure behavior,
- metrics must be explainable,
- and users need a product, not just a query.

## Working Style

I like practical systems with visible correctness: idempotent ingestion, tested transformations, explicit handling of unknown values, small APIs, and documentation that explains the decisions behind the code.
