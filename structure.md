# Database Auto

## (table) Auto

- id BINGINT PRIMARY KEY UNIQUE NOTNULL INDEX
- brand VARCHAR(20) NOTNULL INDEX
- modello VARCHAR(50) NOTNULL INDEX
- versione VARCHAR(50) NULL
- carburante VARCHAR(30) NOTNULL
- cilindrata_cm3 SMALLINT NULL
- cv SMALLINT NULL
- kw SMALLINT NULL
- euro TINYINT NULL
- km MEDIUMINT NOTNULL
- cambio VARCHAR(30) NULL
- prezzo DECIMAL(8,2) NOTNULL
- anno_immatricolazione YEAR NOTNULL INDEX
- colore VARCHAR(50) NULL
- cerchi VARCHAR(30) NULL
- carrozzeria VARCHAR(100) NULL
- interni VARCHAR(100) NULL
- colore_interni VARCHAR(50) NULL
- optional VARCHAR(255) NULL
- descrizione TEXT NULL
- garanzia VARCHAR(100) NULL
