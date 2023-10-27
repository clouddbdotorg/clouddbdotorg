# Cloud Data Warehouse Comparison

|SQL Support      |Snowflake|AWS Redshift|Google Bigquery|Databricks|Oracle|Exasol|
|---------------------------|---------|------------|---------------|----------|------|------|
| MATCH_RECOGNIZE           | Yes     |❌          | ❌            |❌        |Yes   |❌    |
| QUALIFY                   |Yes      |Yes         |Yes            |Yes       |Yes   |Yes   |
| SKYLINE                   |❌       |❌          |❌             |❌        |❌    |Yes   |
|GRAPH_TABLE                |❌       |❌          |❌             |❌        |Yes   |❌    |
|MIN_BY / MAX_BY            |Yes      |❌          |Yes            |Yes       |❌    |❌    |
|GROUP BY CUBE              |Yes      |❌          |Yes            |Yes       |Yes   |Yes   |
|GROUP BY ROLLUP            |Yes      |❌          |Yes            |Yes       |Yes   |Yes   |
|GROUP BY GROUPING SETS     |Yes      |❌          |Yes            |Yes       |Yes   |Yes   |


