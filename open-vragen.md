# Examen Databases Open Vragen

Datum: 17/06/2022

## Instructies

Lees deze instructies zeer zorgvuldig.

Beantwoord de vragen door een SQL query en output result in de respectievelijke velden sql en text in te vullen. 

```sql
SELECT example FROM answer;
```

```text
+---------+
| example |
+---------+
|      42 |
+---------+
```

**Beperk het aantal rijen in het antwoord tot 15.**

**Geef enkel de gevraagde kolommen terug in alle queries.**

Tip het database ER diagram:

![Sakila ER diagram](./img/sakila-schema.png)

## Vragen

### Vraag 0

Onder de folder source vind je sakila-data.sql en sakila-schema.sql terug. Voer de scripts uit en toon alle data die in de *language* tabel terug te vinden is.

```sql
SOURCE sakila-data.sql;
SOURCE sakila-schema.sql;
SELECT * FROM language;
```

```text
+-------------+----------+---------------------+
| language_id | name     | last_update         |
+-------------+----------+---------------------+
|           1 | English  | 2006-02-15 05:02:19 |
|           2 | Italian  | 2006-02-15 05:02:19 |
|           3 | Japanese | 2006-02-15 05:02:19 |
|           4 | Mandarin | 2006-02-15 05:02:19 |
|           5 | French   | 2006-02-15 05:02:19 |
|           6 | German   | 2006-02-15 05:02:19 |
+-------------+----------+---------------------+
```

### Vraag 1

Maak 1 query voor:

1. Geef alle acteurs hun voornaam en familienaam terug waarvan hun familienaam begint met een 'T'.
1. De antwoorden dienen in 1 kolom genaamd 'Actor Name' teruggegeven te worden.
1. Allemaal in kleine letters met een spatie tussen de voornaam en de familienaam.
1. Gesorteerd volgens familienaam en indien dezelfde familienaam ook nog gesorteerd volgens voornaam.

```sql
SELECT LOWER(CONCAT(first_name,' ', last_name)) AS 'Actor Name' 
FROM actor 
WHERE last_name LIKE 'T%'
ORDER BY last_name, first_name;
```

```text
+----------------+
| Actor Name     |
+----------------+
| ian tandy      |
| mary tandy     |
| dustin tautou  |
| burt temple    |
| mena temple    |
| russell temple |
| thora temple   |
| frances tomei  |
| dan torn       |
| kenneth torn   |
| walter torn    |
| lucille tracy  |
| renee tracy    |
+----------------+
```

### Vraag 2

Maak 1 query voor:

1. Geef de totale inkomsten (terug te vinden in de payment tabel) van juni 2005.
1. Geef het antwoord de naam 'Total income June 2005'.

```sql
SELECT SUM(amount) AS 'Total income June 2005' FROM payment 
WHERE Year(payment_date) = '2005' AND Month(payment_date) = '6'; 
```

```text
+------------------------+
| Total income June 2005 |
+------------------------+
|                9631.88 |
+------------------------+
```

### Vraag 3

Maak 1 query:

1. Om te bepalen in hoeveel films de acteur 'CARMEN HUNT' heeft meegespeeld.
1. Maak gebruik van subqueries.
1. Geef het antwoord de naam 'Number of films with Carmen Hunt'.

```sql
SELECT COUNT(*) AS 'Number of films with Carmen Hunt' FROM film_actor WHERE actor_id IN 
(SELECT actor_id FROM actor WHERE first_name = 'CARMEN' AND last_name = 'HUNT'); 
```

```text
+----------------------------------+
| Number of films with Carmen Hunt |
+----------------------------------+
|                               26 |
+----------------------------------+
```

### Vraag 4

Maak 1 query:

1. Maak 1 query om een lijst van alle film titels uit de categorie 'New' weer te geven.
1. Maak gebruik van JOINS.
1. Beperk het aantal films in de output tot 15.

```sql
SELECT title FROM film 
INNER JOIN film_category ON film.film_id = film_category.film_id
INNER JOIN category ON film_category.category_id = category.category_id
WHERE category.name = 'New'
LIMIT 15; 
```

```text
+----------------------+
| title                |
+----------------------+
| AMISTAD MIDSUMMER    |
| ANGELS LIFE          |
| APOCALYPSE FLAMINGOS |
| ATTRACTION NEWTON    |
| BIRDS PERDITION      |
| BOULEVARD MOB        |
| BRANNIGAN SUNRISE    |
| BREAKFAST GOLDFINGER |
| BREAKING HOME        |
| BUTCH PANTHER        |
| BUTTERFLY CHOCOLAT   |
| CHAPLIN LICENSE      |
| CHINATOWN GLADIATOR  |
| CLEOPATRA DEVIL      |
| CLYDE THEORY         |
+----------------------+
```

### Vraag 5

Maak 1 query voor:

1. Geef per personeelslid de gemiddelde prijs van een betaling uit juni 2005.
1. Voornaam en familienaam van het personeelslid dienen in 1 kolom genaamd 'Employee' teruggegeven te worden met een spatie tussen voornaam en familienaam.

```sql
SELECT CONCAT(first_name,' ', last_name) AS Employee, AVG(amount) FROM payment
INNER JOIN staff ON payment.staff_id = staff.staff_id
WHERE Year(payment_date) = '2005' AND Month(payment_date) = '6'
GROUP BY payment.staff_id;
```

```text
+--------------+-------------+
| Employee     | AVG(amount) |
+--------------+-------------+
| Mike Hillyer |    4.103402 |
| Jon Stephens |    4.229547 |
+--------------+-------------+
```

### Vraag 6

Maak 1 query voor:

1. Geef voornaam, familienaam, adres, postcode, stad, land en het totale bedrag van de klant die het meest heeft uitgegeven.

```sql
SELECT first_name, last_name, address, postal_code, city, country, SUM(amount) FROM customer
INNER JOIN address ON customer.address_id = address.address_id
INNER JOIN city ON address.city_id = city.city_id
INNER JOIN country ON city.country_id = country.country_id
INNER JOIN payment ON customer.customer_id = payment.customer_id
GROUP BY payment.customer_id ORDER BY SUM(amount) DESC LIMIT 1;
```

```text
+------------+-----------+------------------+-------------+------------+---------------+-------------+
| first_name | last_name | address          | postal_code | city       | country       | SUM(amount) |
+------------+-----------+------------------+-------------+------------+---------------+-------------+
| KARL       | SEAL      | 1427 Tabuk Place | 31342       | Cape Coral | United States |      221.55 |
+------------+-----------+------------------+-------------+------------+---------------+-------------+
```

### Vraag 7

Maak 1 query voor:

1. Geef voornaam, familienaam, adres, postcode, stad, land en het totale bedrag van de klant die het meest heeft uitgegeven.

```sql

```

```text

```
