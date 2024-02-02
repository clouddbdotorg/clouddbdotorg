# Cloud Data Warehouse Comparison

|Advance Analytical Functions                                                      |Snowflake   |AWS Redshift|Google Bigquery|Databricks |Oracle|Exasol|
|---------------------------------------------------------------------------------------|------------|------------|---------------|-----------|------|------|
|[MATCH_RECOGNIZE](https://queried.org/applied-overview-of-MATCH_RECOGNIZE-clause.html) |✅          |❌          |❌             |❌        |✅    |❌    |
|QUALIFY                                                                                |✅          |✅          |✅             |✅        |✅    |✅    |
|SKYLINE                                                                                |❌          |❌          |❌             |❌        |❌    |✅    |
|GRAPH_TABLE                                                                            |❌          |❌          |❌             |❌        |✅    |❌    |
|[MIN_BY](https://queried.org/min_by.html) / [MAX_BY](https://queried.org/max_by.html)  |✅          |❌          |✅             |✅        |❌    |❌    |
|GROUP BY CUBE                                                                          |✅          |❌          |✅             |✅        |✅    |✅    |
|GROUP BY ROLLUP                                                                        |✅          |❌          |✅             |✅        |✅    |✅    |
|GROUP BY GROUPING SETS                                                                 |✅          |❌          |✅             |✅        |✅    |✅    |
|[CONDITIONAL_TRUE_EVENT](https://queried.org/conditional_true_event.html)              |✅          |❌          |❌             |❌        |❌    |❌    |
|CONDITIONAL_CHANGE_EVENT                                                               |✅          |❌          |❌             |❌        |❌    |❌    |
|IS DISTINCT FROM / IS NOT DISTINCT FROM                                                |✅          |❌          |✅             |✅        |❌    |❌    |
|IS DISTINCT FROM / IS NOT DISTINCT FROM                                                |✅          |❌          |✅             |✅        |❌    |❌    |
|[ASOF + MATCH_CONDITION join](https://queried.org/ASOF-and-MATCH_CONDITION-join.html)  |✅          |❌          |❌             |❌        |❌    |❌    |
