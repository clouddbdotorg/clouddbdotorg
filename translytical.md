# Translytical Database

|Translytical Database|Strategy|
|---------------------|--------|
|SQL DB in Microsoft Fabric| All data is replicated in near-real time to open-source delta parquet format in OneLake. When you deploy a SQL database in Fabric, you get two endpoints: an endpoint to the database and a "SQL analytics endpoint" that allows querying the replicated data in OneLake. This unifies operational and analytics work without having to move any data. With the SQL analytics endpoint, you can query using the data warehouse engine.
|TiDB|Real-time replication of data from OLTP Table to Columnar [TiFlash](https://docs.pingcap.com/tidb/stable/tiflash-overview) tables. Analytical queries are served by the TiFlash Columnar tables. |
|AlloydDB|Enable the Columnar Engine on the AlloyDB and then either manually add columns to the Columnar Engine or use auto-columnarization, which analyzes your workload and automatically adds columns.|
