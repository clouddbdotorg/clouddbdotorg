# Cloud Data Warehouse Comparison

|Advance Analytical Functions                                                                        |Snowflake   |AWS Redshift|Google Bigquery|Databricks |Oracle|Exasol|
|----------------------------------------------------------------------------------------------------|------------|------------|---------------|-----------|------|------|
|[MATCH_RECOGNIZE](https://qosf.com/applied-overview-of-MATCH_RECOGNIZE-clause.html)                 |✅          |❌          |❌             |❌        |✅    |❌    |
|QUALIFY                                                                                             |✅          |✅          |✅             |✅        |✅    |✅    |
|SKYLINE                                                                                             |❌          |❌          |❌             |❌        |❌    |✅    |
|GRAPH_TABLE                                                                                         |❌          |❌          |❌             |❌        |✅    |❌    |
|[MIN_BY](https://qosf.com/min_by.html) / [MAX_BY](https://qosf.com/max_by.html)                     |✅          |❌          |✅             |✅        |❌    |❌    |
|GROUP BY CUBE                                                                                       |✅          |❌          |✅             |✅        |✅    |✅    |
|GROUP BY ROLLUP                                                                                     |✅          |❌          |✅             |✅        |✅    |✅    |
|GROUP BY GROUPING SETS                                                                              |✅          |❌          |✅             |✅        |✅    |✅    |
|[CONDITIONAL_TRUE_EVENT](https://qosf.com/conditional_true_event.html)                              |✅          |❌          |❌             |❌        |❌    |❌    |
|CONDITIONAL_CHANGE_EVENT                                                                            |✅          |❌          |❌             |❌        |❌    |❌    |
|[RATIO_TO_REPORT](https://qosf.com/ratio_to_report.html)                                            |✅          |✅          |❌             |❌        |✅    |✅    |
|[IS DISTINCT FROM](https://qosf.com/null-safe-comparison-in-snowflake-sql.html)                     |✅          |❌          |✅             |✅        |❌    |❌    |
|[IS NOT DISTINCT FROM](https://qosf.com/null-safe-comparison-in-snowflake-sql.html)                 |✅          |❌          |✅             |✅        |❌    |❌    |
|[ASOF join](https://qosf.com/ASOF-join.html)                                                        |✅          |❌          |✅             |❌        |❌    |❌    |
|[SQL ASOF join](https://qosf.com/ASOF-and-MATCH_CONDITION-join.html)                                |✅          |❌          |✅             |❌        |❌    |❌    |
|[RANGE_SESSIONIZE](https://qosf.com/sessionization-using-RANGE_SESSIONIZE-in-google-big-query.html) |❌          |❌          |✅             |❌        |❌    |❌    | 
 
