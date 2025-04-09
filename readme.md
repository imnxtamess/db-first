# Cars DB

## Table name : `cars`

**Columns**

- ID - VARCHAR(255) - NOTNULL - UNIQUE - AUTO_INCREMENT - PRIMARY_KEY
- Model Name: - VARCHAR(255) - NOTNULL
- Colour: - VARCHAR(30) - NULL
- isNew? : - TINYINT (0 or 1) - NOTNULL
- PlateNumber: - VARCHAR(20) - NULL - UNIQUE
- Year: - YEAR - NOTNULL
- KM: - INT - NOTNULL
- Price: - DECIMAL(8,2) - NULL
- Category: - VARCHAR(50) - NULL
