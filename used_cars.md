# Table structure of "Used Cars"

| Nome colonna       | Tipo di dato  | Attributi                      | Indice      |
| ------------------ | ------------- | ------------------------------ | ----------- |
| id                 | BIGINT        | UNIQUE, NOT NULL, UNSIGNED, AI | PRIMARY KEY |
| vin                | CHAR(17)      | UNIQUE, NOT NULL               | INDEX       |
| brand              | VARCHAR(50)   | NOT NULL                       | INDEX       |
| model              | VARCHAR(50)   | NOT NULL                       | INDEX       |
| version            | VARCHAR(50)   | NULL                           |             |
| year               | YEAR          | NOT NULL                       |             |
| first_registration | DATE          | NULL                           |             |
| mileage            | INT           | NOT NULL                       |             |
| fuel_type          | VARCHAR(20)   | NOT NULL                       |             |
| transmission       | VARCHAR(20)   | NOT NULL                       |             |
| power_hp           | SMALLINT      | NULL                           |             |
| engine_capacity    | INT           | NULL                           |             |
| color              | VARCHAR(30)   | NULL                           |             |
| doors              | TINYINT       | NULL                           |             |
| seats              | TINYINT       | NULL                           |             |
| owners_count       | TINYINT       | NULL                           |             |
| condition          | VARCHAR(20)   | NOT NULL                       |             |
| price              | DECIMAL(10,2) | NOT NULL                       | INDEX       |
| description        | TEXT          | NULL                           |             |
| image_url          | VARCHAR(255)  | NULL                           |             |
| available          | BOOLEAN       | DEFAULT TRUE                   | INDEX       |
