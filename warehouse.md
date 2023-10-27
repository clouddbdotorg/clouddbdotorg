# Cloud Data Warehouse Comparison

|SQL Support      |Snowflake|AWS Redshift|Google Bigquery|Databricks|Oracle|Exasol|
|---------------------------|------------|------------|---------------|-----------|------|------|
| MATCH_RECOGNIZE           |✅          |❌          | ❌            |❌        |✅    |❌    |
| QUALIFY                   |✅          |✅          |✅             |✅        |✅    |✅    |
| SKYLINE                   |❌          |❌          |❌             |❌        |❌    |✅    |
|GRAPH_TABLE                |❌          |❌          |❌             |❌        |✅    |❌    |
|MIN_BY / MAX_BY            |✅          |❌          |✅             |✅        |❌    |❌    |
|GROUP BY CUBE              |✅          |❌          |✅             |✅        |✅    |✅    |
|GROUP BY ROLLUP            |✅          |❌          |✅             |✅        |✅    |✅    |
|GROUP BY GROUPING SETS     |✅          |❌          |✅             |✅        |✅    |✅    |


