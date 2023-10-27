# Cloud Data Warehouse Comparison

|SQL Support      |Snowflake|AWS Redshift|Google Bigquery|Databricks|Oracle|Exasol|
|---------------------------|------------|------------|---------------|-----------|------|------|
| MATCH_RECOGNIZE           |✅          |❌          | ❌            |❌        |Yes   |❌    |
| QUALIFY                   |✅          |✅          |✅             |✅        |Yes   |Yes   |
| SKYLINE                   |❌       |❌          |❌             |❌        |❌    |Yes   |
|GRAPH_TABLE                |❌       |❌          |❌             |❌        |Yes   |❌    |
|MIN_BY / MAX_BY            |✅       |❌          |✅             |✅        |❌    |❌    |
|GROUP BY CUBE              |✅       |❌          |✅             |✅        |Yes   |Yes   |
|GROUP BY ROLLUP            |✅       |❌          |✅             |✅        |Yes   |Yes   |
|GROUP BY GROUPING SETS     |✅       |❌          |✅             |✅        |Yes   |Yes   |


