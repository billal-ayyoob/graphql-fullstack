#GraphQL Full stack tutorial using Apollo Client & Server
The Schema Definations will be under `datasources` directory. Schema is structured in a way that it defines what my applications needs to be able to do and
what actions my client will take. Schema will define what type of data my client can read and write to the Graph.
 
In this tutorial I am using `SpcaceX API` as my primary `REST API` Datasource which will be read only. To store application data like `user identities` and `seat reservation` I am using `SQLite` database and promised-base Sequelize for ORM (Object Relational Mapping) as a custom datasource. Moreover, to populate data into the schema `Resolvers` are being used.
