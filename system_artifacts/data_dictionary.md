# Data Dictionary — GS-KO Platform

| Table      | Column        | Type      | Description                                                |
|------------|--------------|-----------|------------------------------------------------------------|
| Gene       | gene_id      | INT       | Primary key; unique gene identifier                        |
|            | symbol       | VARCHAR   | Gene symbol (e.g. GS, GAPDH)                              |
| KO_Run     | run_id       | INT       | Primary key; unique identifier for each KO experiment      |
|            | gene_id      | INT       | Foreign key; references Gene.gene_id                       |
|            | timestamp    | DATETIME  | Time when the KO simulation run was performed              |
| Flux       | flux_id      | INT       | Primary key; unique identifier for each flux record        |
|            | run_id       | INT       | Foreign key; references KO_Run.run_id                      |
|            | reaction_id  | VARCHAR   | Reaction identifier (e.g. R_GLUt1)                         |
|            | flux_value   | FLOAT     | Computed flux value for the reaction in this KO experiment |

