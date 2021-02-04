# Nome database: Negozio
# Nome tabella: Videogames

* id BIGINT PRIMARYKEY
* titolo string VARCHAR(40) NOTNULL
* descrizione TEXT NULL
* anno_pubblicazione date YEAR NOTNULL
* prezzo number FLOAT(5,2) NULL
* genere string VARCHAR(10) NOTNULL
* edizione string VARCHAR(25) NULL 
* lingua string VARCHAR(15) NOTNULL
* cover-image string VARCHAR() NULL
* sottotitoli string VARCHAR() NULL
* disponibilità int TINYINT NULL DEFAULT(0)
* quantità int SMALLINT NULL DEFAULT(0)
* platform string VARCHAR(50) NULL
* players int TINYINT NULL
* created date DATETIME NOTNULL