# dipartimenti
- id BIGINT AI UNIQUE NOTNULL
- lettere_e_filosofia VARCHAR (100) NOTNULL UNIQUE
- economia VARCHA5 (100) NOTNULL UNIQUE
- ingegneria VARCHAR (100) NOTNULL UNIQUE

## corisi di laurea
- lettere_classiche VARCHAR (100) NOTNULL 
- economia_e_finanza VARCHAR (100) NOTNULL
- ingegneria_informatica VARCHAR (100) NOTNULL 
- data_inzio DATE NOTNULL
- data_fine DATE NOTNULL 

## corsi
- letteratura_italiana VARCHAR (100) NOTNULL
- storia_dell_arte_modrena VARCHAR (75) NOTNULL
- ecomomia aziendale VARCHAR (75) NOTNULL
- marketing VARCHAR (75) NOTNULL
- elettronica_digitale VARCHAR (75) NOTNLL
- chimica VARCHAR (75) NOTNULL
- esami  VARCHAR (75) NULL 

## esami
- cfu SAMLLINT NOTNULL
- voti SMALLINT NOTNULL
- isgenanti VARCHAR (60) NOTNULL 
- studente VARCHAR(60) NOTNULL
- sessione VARCHAR (60) NULL

## cfu
- 3 SMALLINT NOTNULL
- 6 SMALLINT NOTNULL
- 9 SMALLINT NOTNULL 
- 12 SMALLINT NOTNULL

## sessione
- appeli SMALLINT NULL
 ## voti
 - sufficente SMALLINT
 - insufficente SMALLINT

 ## studente 
 - id id BIGINT AI UNIQUE NOTNULL
 - nome VARCHAR(30) NOTNULL
 - cognome VARCHAR(30) NOTNULL
 - data_di_nascita DATE NULL
 - matricola SMALLINT

 ## isegnante
 - id id BIGINT AI UNIQUE NOTNULL
 - nome VARCHAR(30) NOTNULL
 - cognome VARCHAR(30) NOTNULL
 - data_di_nascita DATE NULL 









