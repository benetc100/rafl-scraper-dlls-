# rafl-scraper-dlls-
The initial tables that will be needed to ingest the data from multiple top sites for listings.

## Directory Structure

```
ddl/
├── create_tables/       # CREATE TABLE scripts for all ingestion tables
├── transformations/     # Transformation scripts that reshape / clean raw data
└── stored_procedures/   # Stored procedure scripts used in the scraping workflow
```

### Folder descriptions

| Folder | Purpose |
|--------|---------|
| `ddl/create_tables/` | SQL scripts that define the schema for each target table (e.g. `create_listings.sql`). |
| `ddl/transformations/` | Scripts that transform and load raw scraped data into the target tables. |
| `ddl/stored_procedures/` | Stored procedure definitions called during the scraping and loading workflow. |
