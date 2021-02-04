<!-- Create un file di testo per descrivere un database di un negozio di videogiochi.
Strutturate il file come fatto oggi in classe.  Specificate: il nome del database, la tabella e le potenziali colonne con i tipi di dato. -->

# database name: Game Stock
# table name: Games
- id BIGINT PRIMARYKEY
- cover_img string VARCHAR (200)
- title sting VARCHAR (100)
- description string TEXT
- genre string VARCHAR (50)
- date_relase DATE 
- price_for_copy number FLOAT (3,2)
- mode string VARCHAR (15)
- language string VARCHAR (20)
- director string VARCHAR (20)
- writer string VARCHAR (20)
- developer string VARCHAR (20)
- programmer string VARCHAR (20)
- producer string VARCHAR (20)
- publisher string VARCHAR (20)
- composer string VARCHAR (20)
- engine string VARCHAR (50)
- platform string VARCHAR (100)
- release number TINYINT  