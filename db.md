# "car" TABLE STRUCTURE

| FIELD            | TYPE        | ATTRIBUTES                         | INDEXES     |
| ---------------- | ----------- | ---------------------------------- | ----------- |
| id               | INT         | AUTO INCREMENT, NOT NULL, UNSIGNED | PRIMARY KEY |
| brand            | VARCHAR(20) | NOT NULL                           |             |
| model_name       | VARCHAR(20) | NOT NULL                           |             |
| model_year       | YEAR        | NOT NULL                           |             |
| segment          | VARCHAR(10) | NULL                               |             |
| vin              | CHAR(17)    | NOT NULL, UNIQUE                   |             |
| engine           | FLOAT(2, 1) | NOT NULL                           |             |
| engine_power(CV) | SMALLINT    | NULL                               |             |
| fuel_supply      | VARCHAR(10) | NOT NULL                           |             |
| shift            | VARCHAR(10) | NOT NULL                           |             |
| odometer(km)     | MEDIUMINT   | NOT NULL, DEFAULT('000.000')       |             |
| price(€)         | CURRENCY    | NOT NULL                           |             |
| doors            | CHAR(1)     | NULL                               |             |
| width(mm)        | SMALLINT    | NULL                               |             |
| length(mm)       | SMALLINT    | NULL                               |             |
| height(mm)       | SMALLINT    | NULL                               |             |
| weight(kg)       | SMALLINT    | NULL                               |             |
| conditions(new)  | YES/NO      | NOT NULL                           |             |
