# Cloud Data Warehouse Comparison

|SQL Support      |Snowflake|AWS Redshift|Google Bigquery|Databricks|Oracle|Exasol|
|---------------------------|---------|------------|---------------|----------|------|------|
| MATCH_RECOGNIZE           | Yes     |❌          | No            |No        |Yes   |No    |
| QUALIFY                   |Yes      |Yes         |Yes            |Yes       |Yes   |Yes   |
| SKYLINE                   |No       | No         |No             |No        |No    |Yes   |
|GRAPH_TABLE                |No       |No          |No             |No        |Yes   |No    |
|MIN_BY / MAX_BY            |Yes      |No          |Yes            |Yes       |No    |No    |
|GROUP BY CUBE              |Yes      |No          |Yes            |Yes       |Yes   |Yes   |
|GROUP BY ROLLUP            |Yes      |No          |Yes            |Yes       |Yes   |Yes   |
|GROUP BY GROUPING SETS     |Yes      |No          |Yes            |Yes       |Yes   |Yes   |


