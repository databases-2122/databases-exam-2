# Examen Databases Multiple Choice

Datum: 17/06/2022

## Instructies

Lees deze instructies zeer zorgvuldig.

Een multiple choice vraag bestaat uit een vraag, opties (A,B,C,D) en een antwoord.

Giscorrectie is van toepassing:

* juist antwoord = + 1  
* fout antwoord = - 1 / (n - 1)
* geen antwoord = 0

Vul bij het antwoord de letter in. Indien je geen antwoord wil geven op de vraag plaats dan 'X'.

Voorbeeld vraag:

### Vraag 0

Wat is het antwoord op de vraag van het universum, het leven en alles?

A: Wiskunde

B: Microcontrollers

C: Databases

D: 42

---
oplossing:
    vraag: 0
    antwoord: D
...

Let op dat je de syntax van de oplossing niet aanpast. Vul enkel het antwoord in.

Tip: je kan de markdown preview gebruiken om de vragen te lezen.

Veel succes!

## Vragen

### Vraag 1

Wat is het doel van het `USE` statement in MySQL?

A: De database engine selecteren, bvb. MySQL of MariaDB.

B: Aanmelden op de database.

C: Standaard database opgeven waarop queries uitgevoerd worden indien geen database specifiek opgegeven wordt.

D: Commandline tool om met de database te communiceren.

---
oplossing:
    vraag: 1
    antwoord: C
...

### Vraag 2

Met welk statement kunnen alle kolommen van een tabel opgevraagd worden?

A: `SELECT mytable;`

B: `SELECT all FROM mytable;`

C: `SELECT % FROM mytable;`

D: `SELECT * FROM mytable;`

---
oplossing:
    vraag: 2
    antwoord: D
...

### Vraag 3

Met welk keyword kan je voorkomen dat dubbele resultaten teruggeven worden?

A: `DISTINCT`

B: `UNIQUE`

C: `WHERE`

D: `DOUBLE`

---
oplossing:
    vraag: 3
    antwoord: A
...

### Vraag 4

Welke bewering is correct?

A: `VARCHAR` data neemt meer plaats in dan `CHAR` data.

B: Berekeningen met `DECIMAL` data zijn sneller dan berekeningen met `FLOAT` data.

C: Berekeningen met `FLOAT` data zijn nauwkeuriger dan berekeningen met `DECIMAL` data.

D: Het ophalen van `CHAR` data is sneller dan het ophalen van `VARCHAR` data.

---
oplossing:
    vraag: 4
    antwoord: D
...

### Vraag 5

Welke bewering is correct?

A: De waarden van een Primary Key zijn uniek.

B: Een tabel kan meerdere Primary Keys bevatten.

C: Een Primary Key kan `NULL` bevatten.

D: Een Primary Key is 1 kolom in een tabel.

---
oplossing:
    vraag: 5
    antwoord: A
...

### Vraag 6

Met welk keyword kan je filteren op een berekend veld (calculated field)?

A: `WHERE`

B: `HAVING`

C: `AS`

D: `FROM`

---
oplossing:
    vraag: 6
    antwoord: B
...

### Vraag 7

Hoe wordt een Entiteit-Relatie –ER – diagram genoemd waarin datatypes worden weergegeven?

A: Virtueel

B: Fysiek

C: Conceptueel

D: Logisch

---
oplossing:
    vraag: 7
    antwoord: B
...

### Vraag 8

Welke bewering is correct?

A: Een Foreign Key in een tabel heeft dezelfde waarde als een Primary Key in een andere tabel.

B: De waarden van een Foreign Key zijn uniek.

C: Een tabel kan hoogstens 1 Foreign Key bevatten.

D: Elke tabel heeft een Foreign Key.

---
oplossing:
    vraag: 8
    antwoord: A
...

### Vraag 9

Welke bewering is correct?

A: Het cartesisch product van twee tabellen verkrijg je door een `INNER JOIN` uit te voeren.

B: Een join is de combinatie van data uit twee tabellen.

C: Een join kan uitgevoerd worden zonder expliciet een `JOIN` clausule toe te voegen in de query.

D: Een join zonder `WHERE` clausule is geen geldige SQL syntax.

---
oplossing:
    vraag: 9
    antwoord: C
...

### Vraag 10

Op welke manier kan je instellen dat een gebruiker toegang heeft van overal?

A: `CREATE USER ‘demo’ @ ‘localhost’;`

B: `CREATE USER ‘demo’ @ ‘255.255.255.255’;`

C: `CREATE USER ‘demo’ @ ‘*.*.*.*’;`

D: `CREATE USER ‘demo’ @ ‘%’;`

---
oplossing:
    vraag: 10
    antwoord: D
...

### Vraag 11

Wat is de meest fijnmazige instelling van rechten in SQL?

A: Rechten gelden op alle databases op de server.

B: Rechten kunnen ingesteld worden per tabel.

C: Rechten kunnen ingesteld worden per database.

D: Rechten kunnen ingesteld worden per kolom.

---
oplossing:
    vraag: 11
    antwoord: B
...

### Vraag 12

Met welk statement kunnen alle rechten getoond worden van de gebruiker **user** op **localhost**?

A: `SHOW GRANTS FOR 'user'@'%';`

B: `SHOW GRANTS FOR 'user';`

C: `SHOW GRANTS FOR 'user'@'localhost';`

D: `SHOW GRANTS FOR 'user'@'127.0.0.1';`

---
oplossing:
    vraag: 12
    antwoord: C
...

### Vraag 13

Gegeven de table mysql.user:

+------+-----------+
| User | Host      |
+------+-----------+
| root | 127.0.0.1 |
| root | ::1       |
| user | localhost |
| root | localhost |
+------+-----------+

Met welk statement kan je de MySQL gebruiker 'user' verwijderen?

A: `DROP USER ‘user’;`

B: `DROP USER ‘user’@’localhost’;`

C: `DELETE ‘user’ FROM user;`

D: `DELETE FROM mysql.user;`

---
oplossing:
    vraag: 13
    antwoord: B
...

### Vraag 14

Welke bewering is correct?

A: Voor het hashen van gegevens is een encryptie sleutel nodig.

B: Hashen van gegevens is veiliger wanneer gebruik gemaakt wordt van een vinegar.

C: Een salted hash voorkomt dat een aanvaller de database kan uitlezen.

D: Een hashberekening kan niet ongedaan worden door de omgekeerde bewerking te uit te voeren.

---
oplossing:
    vraag: 14
    antwoord: D
...

### Vraag 15

Met welk hash algoritme kunnen gevoelige gegevens zoals wachtwoorden veiliger in een database opgeslagen worden?

A: Voor het hashen van gegevens is een encryptie sleutel nodig.

B: Hashen van gegevens is veiliger wanneer gebruik gemaakt wordt van een vinegar.

C: Een salted hash voorkomt dat een aanvaller de database kan uitlezen.

D: Een hashberekening kan niet ongedaan worden door de omgekeerde bewerking te uit te voeren.

---
oplossing:
    vraag: 15
    antwoord: D
...

### Vraag 16

Welk MySQL datatype kan gebruikt worden om een lijst van mogelijke waardes op te geven en waarvan meerdere opties opgegeven kunnen worden?

A: `SET`

B: `ENUM`

C: `ARRAY`

D: `LIST`

---
oplossing:
    vraag: 16
    antwoord: A
...

### Vraag 17

Wat is een voorbeeld van de SQL Data Definition Language (DDL) CRUD Update functie?


A: `ALTER COLUMN`

B: `UPDATE`

C: `DROP TABLE`

D: `INSERT INTO`

---
oplossing:
    vraag: 17
    antwoord: A
...

### Vraag 18

Wat is een voorbeeld van de SQL Data Manipulation Language (DML)  CRUD Create functie?

A: `SELECT`

B: `CREATE TABLE`

C: `INNER JOIN`

D: `INSERT INTO`

---
oplossing:
    vraag: 18
    antwoord: D
...

### Vraag 19

Wat is een voorbeeld van de SQL Data Manipulation Language (DML) CRUD Read functie?

A: `ALTER COLUMN`

B: `CREATE TABLE`

C: `INNER JOIN`

D: `INSERT INTO`

---
oplossing:
    vraag: 19
    antwoord: C
...

### Vraag 20

Na het uitvoeren van:

```bash
mysql -u root
```

krijg je volgende foutmelding:

```text
ERROR 2002 (HY000): Can't connect to MySQL server on 'localhost' (10061)
```

Wat is het probleem?

A: Het DBMS is niet opgestart.

B: De host parameter ontbreekt: `mysql -u root -h 127.0.0.1`

C: De paswoord parameter ontbreekt: `mysql -u root -p`

D: Het paswoord ontbreekt: `mysql -u root -p letmein`

---
oplossing:
    vraag: 20
    antwoord: A
...

### Vraag 21

Welke SQL constraint is noodzakelijk voor een Primary Key?

A: `NOT NULL`

B: `AUTO_INCREMENT`

C: `UNIQUE`

D: Geen enkele SQL constraint is noodzakelijk

---
oplossing:
    vraag: 21
    antwoord: D
...

### Vraag 22

Na het uitvoeren van:

```sql
CREATE TABLE employees(
   id int(5) AUTO_INCREMENT,
   name varchar(255) NOT NULL,
   job_description enum('developer', 'manager', 'tester', 'operations') NOT NULL,
   primary key(id)
);

INSERT INTO employees(name, job_description, id)
VALUES
('Nico', 'developer', 42),
('Sille', 'operations', 666),
('Franky', 'manager,tester', 7);
```

krijg je volgende output:

```text
Query OK, 3 rows affected, 1 warning (0.012 sec)
Records: 3 Duplicates: 0 Warnings: 1
```

Wat is de warning?

A: De kolom *id* is AUTO_INCREMENT waardoor je zelf geen waarden mag opgeven.

B: Bij INSERT INTO moet de volgorde van de kolommen *id*, *name*, *job_description* zijn.

C: Het datatype van kolom *job_description* zou SET moeten zijn in plaats van ENUM.

D: De waarde van data in de kolom *id* mag niet groter zijn dan 5.

---
oplossing:
    vraag: 22
    antwoord: C
...
