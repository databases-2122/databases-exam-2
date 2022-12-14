# Examen Databases Multiple Choice

Datum: 18/08/2022

## Instructies

Lees deze instructies zeer zorgvuldig.

Een multiple choice vraag bestaat uit een vraag, opties (A,B,C,D) en een antwoord.

Giscorrectie is van toepassing:

* juist antwoord = + 1  
* fout antwoord = - 1 / (n - 1)
* geen antwoord = 0

Vul bij het antwoord de letter in. Indien je geen antwoord wil geven op de vraag plaats dan 'X'. Het HTML commentaar moet je verwijderen. 

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

Wat is de `mysql` tool in XAMPP?

A: Tool om de database engine te selecteren, bvb. MySQL of MariaDB.

B: Tool om te authenticeren met de database.

C: Tool om de standaard database op te geven waarop queries uitgevoerd worden indien geen database specifiek opgegeven wordt.

D: Commandline tool om met de database te communiceren.

---
oplossing:
    vraag: 1
    antwoord: <!--Antwoord hier -->
...

### Vraag 2

Met welk statement wordt slechts 1 kolom van een tabel opgevraagd?

A: `SELECT mytable;`

B: `SELECT all FROM mytable;`

C: `SELECT % FROM mytable;`

D: `SELECT * FROM mytable;`

---
oplossing:
    vraag: 2
    antwoord: <!--Antwoord hier -->
...
### Vraag 3

Met welk keyword kan je filteren in een query?

A: `DISTINCT`

B: `UNIQUE`

C: `WHERE`

D: `DOUBLE`

---
oplossing:
    vraag: 3
    antwoord: <!--Antwoord hier -->
...

### Vraag 4

Welke bewering is correct?

A: `VARCHAR` data neemt meer plaats in dan `CHAR` data.

B: Berekeningen met `DECIMAL` data zijn trager dan berekeningen met `FLOAT` data.

C: Berekeningen met `FLOAT` data zijn nauwkeuriger dan berekeningen met `DECIMAL` data.

D: Het ophalen van `CHAR` data is trager dan het ophalen van `VARCHAR` data.

---
oplossing:
    vraag: 4
    antwoord: <!--Antwoord hier -->
...


### Vraag 5

Welke bewering is correct?

A: De waarden van een Primary Key zijn niet altijd uniek.

B: Een Primary Key kan uit meerdere kolommen bestaan.

C: Een Primary Key kan `NULL` bevatten.

D: Een Primary Key is 1 kolom in een tabel.

---
oplossing:
    vraag: 5
    antwoord: <!--Antwoord hier -->
...

### Vraag 6

Met welk keyword kan je filteren op een berekend veld een naam geven?

A: `WHERE`

B: `HAVING`

C: `AS`

D: `FROM`

---
oplossing:
    vraag: 6
    antwoord: <!--Antwoord hier -->
...

### Vraag 7

Hoe wordt een Entiteit-Relatie ???ER ??? diagram genoemd waarin gegarandeerd alle tabellen worden weergegeven?

A: Virtueel

B: Fysiek

C: Conceptueel

D: Logisch

---
oplossing:
    vraag: 7
    antwoord: <!--Antwoord hier -->
...

### Vraag 8

Welke bewering is correct?

A: Een Foreign Key is legt een relatie met de Primary Key van dezelfde tabel.

B: Als de waarden van een Foreign Key uniek zijn dan is er sprake van een 1-op-1 relatie tussen de tabellen.

C: Een tabel kan hoogstens 1 Foreign Key bevatten.

D: Elke tabel heeft een Foreign Key.

---
oplossing:
    vraag: 8
    antwoord: <!--Antwoord hier -->
...

### Vraag 9

Welke bewering is correct?

A: Het cartesisch product van twee tabellen verkrijg je door een `LEFT JOIN` uit te voeren.

B: Een join is de combinatie van data uit twee of meer tabellen.

C: Een join kan uitgevoerd worden zonder expliciet een `JOIN` clausule toe te voegen in de query.

D: Een join zonder `WHERE` clausule is geen geldige SQL syntax.

---
oplossing:
    vraag: 9
    antwoord: <!--Antwoord hier -->
...

### Vraag 10

Op welke manier kan je voorkomen dat een gebruiker toegang heeft van overal?

A: `CREATE USER ???demo??? @ ???localhost???;`

B: `CREATE USER ???demo??? @ ???255.255.255.255???;`

C: `CREATE USER ???demo??? @ ???*.*.*.*???;`

D: `CREATE USER ???demo??? @ ???%???;`

---
oplossing:
    vraag: 10
    antwoord: <!--Antwoord hier -->
...

### Vraag 11

Wat is de meest fijnmazige instelling van rechten in SQL?

A: Rechten gelden op alle databases op de server.

B: Rechten kunnen ingesteld worden per tabel.

C: Rechten kunnen ingesteld worden per rij.

D: Rechten kunnen ingesteld worden per kolom.

---
oplossing:
    vraag: 11
    antwoord: <!--Antwoord hier -->
...

### Vraag 12

Met welk statement kunnen alle rechten getoond worden van de gebruiker **user**?

A: `SHOW GRANTS FOR 'user'@'%';`

B: `SHOW GRANTS FOR 'user';`

C: `SHOW GRANTS FOR 'user'@'localhost';`

D: `SHOW GRANTS FOR 'user'@'127.0.0.1';`

---
oplossing:
    vraag: 12
    antwoord: <!--Antwoord hier -->
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

A: `DROP USER ???user???;`

B: `DROP USER ???user???@???localhost???;`

C: `DELETE ???user??? FROM user;`

D: `DELETE FROM mysql.user;`

---
oplossing:
    vraag: 13
    antwoord: <!--Antwoord hier -->
...

### Vraag 14

Welke bewering is correct?

A: Voor het hashen van gegevens is een encryptie sleutel nodig.

B: Twee hashes die hetzelfde zijn, hadden dezelfde input voor het hashalgoritme.

C: Een salted hash voorkomt dat een aanvaller de database kan uitlezen.

D: Een hashberekening kan ongedaan worden gemaakt door de omgekeerde bewerking te uit te voeren.

---
oplossing:
    vraag: 14
    antwoord: <!--Antwoord hier -->
...

### Vraag 15

Welk hash algoritme voor opslag in een database van gevoelige gegevens zoals wachtwoorden is verouderd en onveilig?

A: DES

B: SHA-3

C: MD-5

D: Bcrypt

---
oplossing:
    vraag: 15
    antwoord: <!--Antwoord hier -->
...

### Vraag 16

Welk MySQL datatype kan gebruikt worden om een lijst van mogelijke waardes op te geven en waarvan slechts 1 optie opgegeven kan worden?

A: `SET`

B: `ENUM`

C: `ARRAY`

D: `LIST`

---
oplossing:
    vraag: 16
    antwoord: <!--Antwoord hier -->
...

### Vraag 17

Wat is een voorbeeld van de SQL Data Definition Language (DDL) CRUD Delete functie?

A: `ALTER COLUMN`

B: `UPDATE`

C: `DROP TABLE`

D: `INSERT INTO`

---
oplossing:
    vraag: 17
    antwoord: <!--Antwoord hier -->
...

### Vraag 18

Wat is een voorbeeld van de SQL Data Manipulation Language (DML) CRUD Create functie?

A: `SELECT`

B: `CREATE TABLE`

C: `INNER JOIN`

D: `INSERT INTO`

---
oplossing:
    vraag: 18
    antwoord: <!--Antwoord hier -->
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
    antwoord: <!--Antwoord hier -->
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
    antwoord: <!--Antwoord hier -->
...

### Vraag 21

Welke SQL constraint zorgt voor het automatisch invullen van data?

A: `NOT NULL`

B: `AUTO_INCREMENT`

C: `UNIQUE`

D: `CREATE INDEX`

---
oplossing:
    vraag: 21
    antwoord: <!--Antwoord hier -->
...

### Vraag 22

Na het uitvoeren van:

```sql
CREATE TABLE employees(
   id int(5) AUTO_INCREMENT NOT NULL,
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

Wat is de oorzaak van de warning?

A: De kolom *id* is AUTO_INCREMENT waardoor je zelf geen waarden mag opgeven.

B: Bij INSERT INTO moet de volgorde van de kolommen *id*, *name*, *job_description* zijn.

C: Het datatype van kolom *job_description* zou SET moeten zijn in plaats van ENUM.

D: De waarde van data in de kolom *id* mag niet groter zijn dan 5.

---
oplossing:
    vraag: 22
    antwoord: <!--Antwoord hier -->
...

### Vraag 23

Na het uitvoeren van:

```sql
CREATE TABLE employees(
   id int(5) AUTO_INCREMENT NOT NULL,
   name varchar(255) NOT NULL,
   job_description enum('dev', 'test', 'ops'),
   primary key(id)
);

INSERT INTO employees(name, job_description, id)
VALUES
('Nico', 'dev', 42),
('Sille', 'ops', 666),
('Franky', 'test', 7);

ALTER TABLE employees MODIFY COLUMN job_description enum('developer', 'operations', 'tester');

```

krijg je volgende output:

```text
Query OK, 3 rows affected, 3 warnings (0.097 sec)
Records: 3  Duplicates: 0  Warnings: 3
```

Wat is de oorzaak van de warning?

A: De volgorde van waardes in de enum houden niet de juiste volgorde aan.

B: De nieuwe namen in de enum zorgen ervoor dat data verloren gaat.

C: Bij een `MODIFY COLUMN` dienen alle kolommen van de tabel opnieuw gedefinieerd te worden.

D: De nieuwe namen in de enum worden automatisch overgenomen waardoor records zijn aangepast.

---
oplossing:
    vraag: 23
    antwoord: <!--Antwoord hier -->
...

### Vraag 24

Na het uitvoeren van:

```sql
CREATE TABLE employees(
   id int(5) AUTO_INCREMENT NOT NULL,
   name varchar(255) NOT NULL,
   job_description enum('dev', 'test', 'ops'),
   primary key(id)
);

INSERT INTO employees(name, job_description, id)
VALUES
('Nico', 'dev', 42),
('Sille', 'ops', 666),
('Franky', 'test', 7);

CREATE TABLE teachers(
   id int(5) AUTO_INCREMENT NOT NULL,
   name varchar(255) NOT NULL,
   task varchar(255) NOT NULL,
   primary key(id)
);

INSERT INTO teachers(
    task,
    name,
    id    
)
SELECT name, job_description, id FROM employees;

```

Wat is een mogelijk probleem bij het uitvoeren van deze queries?

A: Alle records van employees worden in *teachers* gekopieerd, maar er worden nieuwe id's in de tabel *teachers* aangemaakt.

B: Alle records van employees worden in *teachers* gekopieerd, maar de kolommen *name* en *task* zijn omgewisseld.

C: Er worden geen records gekopieerd doordat het type van de kolom *task* niet overeen komt met het type van de kolom *job_description*.

D: De tabel *employees* is leeg doordat alle records zijn verplaatst naar *teachers*.

---
oplossing:
    vraag: 24
    antwoord: <!--Antwoord hier -->
...

### Vraag 25

Bij het uitvoeren van een query:

```sql
UPDATE employees
SET name = 'Jonas';
```

Wat is een mogelijk probleem?

A: Deze query zal niets veranderen in de tabel als er geen record met als naam 'Jonas' bestaat.

B: Deze query selecteert enkel de records met als naam 'Jonas' en maakt deze NULL.

C: Door het ontbreken van een `WHERE` clausule in de query zijn alle namen veranderd in 'Jonas'.

D: Door het ontbraken van een `SELECT` clausule zal er niets veranderen in te tabel.

---
oplossing:
    vraag: 25
    antwoord: <!--Antwoord hier -->
...

### Vraag 26

Met welke query is het mogelijk volgende uitvoer te verkrijgen?

```text
+----------------+-------------+
| cust_name      | cust_city   |
+----------------+-------------+
| Bugs Bunny     | Chicago     |
| Elmer Fudd     | Chicago     |
| Mouse House    | Columbus    |
| Coyote Inc.    | Detroit     |
| Tasmania Devil | Detroit     |
| Daffy Duck     | Los Angeles |
| Pep E. LaPew   | Los Angeles |
| Wascals        | Muncie      |
| Yosemite Place | Phoenix     |
+----------------+-------------+
```

A: `SELECT cust_name, cust_city FROM customers ORDER BY cust_city, cust_name;`

B: `SELECT cust_name, cust_city FROM customers ORDER BY cust_name, cust_city;`

C: `SELECT cust_name, cust_city FROM customers ORDER BY cust_name DESC, cust_city;`

D: `SELECT cust_name, cust_city FROM customers ORDER BY cust_name ASC, cust_city;`

---
oplossing:
    vraag: 26
    antwoord: <!--Antwoord hier -->
...

### Vraag 27

Met welke query is het mogelijk om de laatste 3 records volgens *finish_number* in oplopende volgorde op te vragen?

Gewenste output:

```text
+---------------+--------------+
| finish_number | name         |
+---------------+--------------+
|            90 | Alina        |
|            91 | Bob          |
|            92 | Chelsea      |
+---------------+--------------+
```

A: `SELECT * FROM (SELECT finish_number, name FROM runners ORDER BY finish_number DESC LIMIT 3) AS list ORDER BY finish_number;`

B: `SELECT finish_number, name FROM runners ORDER BY finish_number LIMIT 3, 3;`

C: `SELECT * FROM (SELECT finish_number, name FROM runners ORDER BY finish_number DESC) AS list ORDER BY finish_number LIMIT 3;`

D: `SELECT * FROM (SELECT finish_number, name FROM runners ORDER BY finish_number DESC) AS list ORDER BY finish_number LIMIT 3, 3;`

---
oplossing:
    vraag: 27
    antwoord: <!--Antwoord hier -->
...

### Vraag 28

Gegeven een (gedeeltelijke) tabel met metadata van sensoren:

```text
+---------------+--------------+
| sensor_id     | city         |
+---------------+--------------+
|            42 | Brugge       |
|            63 | Brugge       |
|            99 | Oostende     |
+---------------+--------------+
```

Hoe kan het aantal steden met sensoren uit deze tabel gevonden worden?

A: `SELECT COUNT(*) FROM sensors;`

B: `SELECT COUNT(DISTINCT city) FROM sensors;`

C: `SELECT COUNT(UNIQUE city) FROM sensors;`

D: `COUNT(DISTINCT(SELECT city FROM sensors);`

---
oplossing:
    vraag: 28
    antwoord: <!--Antwoord hier -->
...

### Vraag 29

Gegeven volgende data:

```text
+---------------+--------------+---------------+--------------+--------------+--------------------+--------------+
| sensor_id     | city         | sensor_type   | zip          | owner        | in_operation_since | e-mail       |
+---------------+--------------+---------------+--------------+--------------+--------------------+--------------+
|            42 | Brugge       |    temperatuur| 8000         | Sille        | 2022-01-01 12:00:00| yy@zz.com    |
|            63 | Brugge       |    vochtigheid| 8000         | Nico         | 2021-05-05 12:00:00| bb@aa.be     |
|            99 | Oostende     |    temperatuur| 8400         | Sille        | 2022-04-01 12:00:00| yy@zz.com    |
+---------------+--------------+---------------+--------------+--------------+--------------------+--------------+
```

Welke tabellen maak je om de database in 2e normaalvorm (2NF) te krijgen?

A: Sensors tabel met kolommen id, type_id, in_operation_since, city, zip owner_id + Sensortypes tabel met type_id, description + Owners tabel met kolommen id, name, e-mail

B: Sensors tabel met kolommen id, type_id, in_operation_since, city_id, owner_id + Sensortypes tabel met type_id, description + Owners tabel met kolommen id, name, e-mail + Cities tabel met kolommen city_id, city_name, city_zip

C: Sensors tabel met kolommen id, type, in_operation_since, city_id, owner_id + Owners tabel met kolommen id, name, e-mail + Cities tabel met kolommen city_id, city_name, city_zip

D: Sensors tabel met kolommen id, type, in_operation_since, city, zip, owner_id + Owners tabel met kolommen id, name, e-mail

---
oplossing:
    vraag: 29
    antwoord: <!--Antwoord hier -->
...

### Vraag 30

Gegeven volgend ER diagram:

![ER diagram](./img/er-example.drawio.png)

Welke uitspraak is waar over dit ER diagram?

A: Een map kan slechts bij 1 sessie gebruikt worden.

B: Elke map heeft altijd 1 sessie met een 0 tot N spelers.

C: Een sessie bestaat uit hoogstens 1 speler op 1 map.

D: Een sessie kan niet zonder map of spelers bestaan.

---
oplossing:
    vraag: 30
    antwoord: <!--Antwoord hier -->
...
