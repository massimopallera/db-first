# DB-FIRST

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

### Table Name: auto_usate

#### Columns:

- TARGA | AI PK(UNIQUE, NOT_NULL) 
- MARCA | VARCHAR(50) NOT_NULL 
- MODELLO | VARCHAR(70) NOT_NULL 
- DESCRIZIONE | VARCHAR(255) NOT_NULL
- KM_FATTI | INT NOT_NULL
- ANNO | YEAR 
- PREZZO | DECIMAL NOT_NULL 
- ?DISPONIBILE | TINYINT 
- CAMBIO | VARCHAR(30) 
- ALIMENTAZIONE | VARCHAR(30) NOT_NULL