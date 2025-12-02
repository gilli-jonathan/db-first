<!-- NOME DEL MIO DB -->
auto-usate

<!-- COLONNE CON I VALORI (?) -->

- ID big pk ai -not null

- DATA_INSERZIONE date -not null

- MARCA varchar(20) -not null
- MODELLO varchar(20) -not null
- ANNO_DI_FABBRICAZIONE year -not null
- COLORE varchar(10) -not null
- TARGA varchar(10) - null unique
- MOTORE varrchar(30) - null
- CAVALLI mediumint - null
- KILOMETRAGGIO int -not null
- CARBURANTE varchar(10) -not null
- RIVENDITORE varchar(30) -not null
- DATA_ULTIMA_REVISIONE date - null

<!-- AGGIUNTO IL PREZZO HAHAH -->
- PREZZO decimal(8,2) -not null


