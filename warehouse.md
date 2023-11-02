# Cloud Data Warehouse Comparison

|Advance Analytical Functions                                                      |Snowflake   |AWS Redshift|Google Bigquery|Databricks |Oracle|Exasol|
|----------------------------------------------------------------------------------|------------|------------|---------------|-----------|------|------|
|[MATCH_RECOGNIZE](https://sql.yt/applied-overview-of-MATCH_RECOGNIZE-clause.html) |✅          |❌          | ❌            |❌        |✅    |❌    |
|QUALIFY                                                                           |✅          |✅          |✅             |✅        |✅    |✅    |
|SKYLINE                                                                           |❌          |❌          |❌             |❌        |❌    |✅    |
|GRAPH_TABLE                                                                       |❌          |❌          |❌             |❌        |✅    |❌    |
|[MIN_BY](https://sql.yt/min_by.html) / [MAX_BY](https://sql.yt/max_by.html)       |✅          |❌          |✅             |✅        |❌    |❌    |
|GROUP BY CUBE                                                                     |✅          |❌          |✅             |✅        |✅    |✅    |
|GROUP BY ROLLUP                                                                   |✅          |❌          |✅             |✅        |✅    |✅    |
|GROUP BY GROUPING SETS                                                            |✅          |❌          |✅             |✅        |✅    |✅    |
|[CONDITIONAL_TRUE_EVENT](https://sql.yt/conditional_true_event.html)              |✅          |❌          |❌             |❌        |❌    |❌    |
|CONDITIONAL_CHANGE_EVENT                                                          |✅          |❌          |❌             |❌        |❌    |❌    |
|IS DISTINCT FROM / IS NOT DISTINCT FROM                                           |✅          |❌          |✅             |✅        |❌    |❌    |
