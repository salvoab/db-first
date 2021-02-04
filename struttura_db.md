# Nome DB: videogame_store

## Nome Tabella: Videogiochi
- ID: numero BIGINT PRIMARY_KEY (AUTO_INCREMENT UNIQUE)
- Titolo: stringa VARCHAR(80) NOTNULL
- Descrizione: stringa VARCHAR(255) NOTNULL
- Copertina: stringa VARCAR(255) NULL
- Sviluppatore: stringa VARCHAR(80) NOTNULL
- Editore: stringa VARCHAR(80) NOTNULL
- Data_di_rilascio: data DATE NOTNULL
- Piattaforma: stringa VARCHAR(20) NOTNULL
- Multiplayer: numero (booleano) TINYINT NOTNULL
- Online_only: numero (booleano) TINYINT NOTNULL
- Voto: numero TINYINT NULL
- Prezzo: numero FLOAT(5,2) NOTNULL

## Nome Tabella: Generi
- ID: numero BIGINT PRIMARY_KEY (AUTO_INCREMENT UNIQUE)
- Genere: stringa VARCHAR(30) NOTNULL