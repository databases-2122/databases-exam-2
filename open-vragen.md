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
<!--Antwoord hier -->
```

```text
<!--Antwoord hier -->
```

### Vraag 1

Maak 1 query voor:

1. Geef alle acteurs hun voornaam en familienaam terug waarvan hun familienaam begint met een 'T'.
1. De antwoorden dienen in 1 kolom genaamd 'Actor Name' teruggegeven te worden.
1. Allemaal in kleine letters met een spatie tussen de voornaam en de familienaam.
1. Gesorteerd volgens familienaam en indien dezelfde familienaam ook nog gesorteerd volgens voornaam.

```sql
<!--Antwoord hier -->
```

```text
<!--Antwoord hier -->
```

### Vraag 2

Maak 1 query voor:

1. De acteur 'GROUCHO WILLIAMS' is van naam veranderd en heet nu 'MARS WILLIAMS', pas dit aan in de database.

```sql
<!--Antwoord hier -->
```

Geef het resultaat van de query ```SELECT * FROM actor WHERE last_name = 'WILLIAMS';```:

```text
<!--Antwoord hier -->
```

### Vraag 3

Maak 1 query voor:

1. Geef de totale inkomsten (terug te vinden in de payment tabel) van juni 2005.
1. Geef het antwoord de naam 'Total income June 2005'.

```sql
<!--Antwoord hier --> 
```

```text
<!--Antwoord hier -->
```

### Vraag 4

Geef het conceptuele ER diagram van de Sakila databank.

![Conceptual ER diagram](./img/conceptual-sakila.png)<!--Antwoord hier -->

### Vraag 5

Maak 1 query:

1. Om te bepalen in hoeveel films de acteur 'CARMEN HUNT' heeft meegespeeld.
1. Maak gebruik van subqueries.
1. Geef het antwoord de naam 'Number of films with Carmen Hunt'.

```sql
<!--Antwoord hier -->
```

```text
<!--Antwoord hier -->
```

### Vraag 6

Maak 1 query:

1. Maak 1 query om een lijst van alle film titels uit de categorie 'New' weer te geven.
1. Maak gebruik van JOINS.
1. Beperk het aantal films in de output tot 15.

```sql
<!--Antwoord hier --> 
```

```text
<!--Antwoord hier -->
```

### Vraag 7

Maak 1 query voor:

1. Geef per personeelslid de gemiddelde prijs van een betaling uit juni 2005.
1. Voornaam en familienaam van het personeelslid dienen in 1 kolom genaamd 'Employee' teruggegeven te worden met een spatie tussen voornaam en familienaam.

```sql
<!--Antwoord hier -->
```

```text
<!--Antwoord hier -->
```

### Vraag 8

Maak 1 query voor:

1. Geef voornaam, familienaam, adres, postcode, stad, land en het totale bedrag van de klant die het meest heeft uitgegeven.

```sql
<!--Antwoord hier -->
```

```text
<!--Antwoord hier -->
```

### Vraag 9

Maak 1 query voor:

1. Geef de volledige stock van de winkel in Lethbridge.
1. Geef de naam van de film en hoeveel keer de winkel de film bezit, noem deze kolom 'stock'.
1. Sorteer de resultaten van meest naar minst en bij evenveel films in stock alfabetisch op titel.
1. Beperk de resultaten in de output tot 15.

```sql
<!--Antwoord hier -->

```

```text
<!--Antwoord hier -->
```

### Vraag 10

Maak 1 query voor:

1. Geef de huidig uitgeleende stock van de winkel in Lethbridge.
1. Geef de naam van de film en hoeveel keer de film uitgeleend is, noem deze kolom 'loaned'.
1. Sorteer de resultaten van meest naar minst en bij evenveel films in stock alfabetisch op titel.
1. Tip: een film die uitgeleend is, heeft als waarde NULL in de kolom *return_date* van tabel *rental*

```sql
<!--Antwoord hier -->
```

```text
<!--Antwoord hier -->
```
