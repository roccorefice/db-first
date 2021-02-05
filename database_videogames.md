# database_nome: videogames shop
# nome_tabella: videogames
- ID PRIMARYKEY AUTO_INCREMENT NOTNULL UNIQUE
- serial_number num MEDIUMINT NOTNULL UNIQUE
- titolo str VARCHAR(30) NOTNULL 
- descrizione str TEXT NULL
- console str VARCHAR(10) NOTNULL
- prezzo num FLOAT(3,2) NOTNULL
- img_copertina str VARCHAR(25) NULL
- edizione str VARCHAR(15) NULL
- peso_installazione(gb) num SMALL NULL
- tipologia str VARCHAR(15) NULL
- disponibilità num TINYINT NULL DEFAULT(0)
- prenotabile num TINYINT NULL DEFAULT(0)
- anno_di_uscita num YEAR NULL
- editore str VARCHAR(15) NULL
- multiplayer num TINYINT NULL
- trailer str VARCHAR(25) NULL
- cross_play num TINYINT NULL
- formato_copertina str VARCHAR(8) NULL
- pegi num VARCHAR(2) NOTNULL
- in_promozione num TINYINT NOTNULL

