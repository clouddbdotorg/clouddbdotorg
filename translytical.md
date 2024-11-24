# Translytical Databases

|Translytical Database|Strategy|
|---------------------|--------|
|SQL DB in Microsoft Fabric| All data is replicated in near-real time to open-source delta parquet format in OneLake. When you deploy a SQL database in Fabric, you get two endpoints: an endpoint to the database and a "SQL analytics endpoint" that allows querying the replicated data in OneLake. This unifies operational and analytics work without having to move any data. With the SQL analytics endpoint, you can query using the data warehouse engine.
