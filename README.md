# NYC Taxi Trip & Revenue Analysis

## Objective

Analyze NYC Yellow Taxi trip data to identify trends in revenue, demand, customer behavior, and pickup or drop-off locations.

## Project Structure

```text
Yellow Trip - Github/
├── data/
│   ├── yellow_tripdata_2026-05.parquet
│   ├── yellow_tripdata_2026-05_sample.csv
│   ├── yellow_tripdata_2026-05_sample.xlsx
│   └── loading_data_to_excel.ipynb
├── analysis/
│   └── cleaned_NYC_Taxi_Analysis.xlsx
├── dashboard/
│   └── Screenshot 2026-09-15 162800.png
└── taxi_zone_lookup_table/
    └── taxi_zone_lookup.csv
```

## Tools and Techniques

- Microsoft Excel
- PivotTables
- PivotCharts
- LOOKUP
- SUMIFS
- COUNTIFS
- Power Query
- Jupyter Notebook
- Parquet and CSV data formats

## Data Sources

The project uses a sample of NYC Yellow Taxi trip data for May 2026 and a taxi-zone lookup table. The Parquet file is the primary trip-data file, while the CSV and Excel files provide smaller, convenient versions for analysis and review.

Official Parquet data source: [yellow_tripdata_2026-05.parquet](https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2026-05.parquet)

## Analysis Workflow

1. Load the trip data in the notebook.
2. Prepare and export data for Excel analysis.
3. Enrich trip records with taxi-zone names using the lookup table.
4. Build summary tables and visualizations in Excel.
5. Review the dashboard and document the resulting business insights.

## Key Insights

1. The 40,000-trip May 2026 sample contains 38,304 valid trips, generating approximately $1,169,566 in recorded revenue, with an average revenue of $30 per trip.
2. The strongest pickup demand occurred around 6 PM, suggesting that evening travel was a major contributor to trip volume in the sample.
3. Manhattan accounted for the largest share of pickup activity and was the dominant pickup borough by trip volume.
4. Manhattan generated the highest recorded revenue among the pickup boroughs, consistent with its leading position in pickup demand.
5. Manhattan - Upper East Side South was the most frequently used pickup zone, with noticeably higher trip volume than the other leading zones.
6. The most frequently observed route was Upper East Side South to Upper East Side North, making it the dominant origin-destination combination in the sample.
7. The sample shows higher average daily pickup demand on weekdays than on weekends.
