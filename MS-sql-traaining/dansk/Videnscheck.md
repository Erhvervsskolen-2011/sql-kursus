# Vidensprøve

200 XP  
5 minutter

1. Du skal returnere en liste over alle salgsmedarbejdere, der har taget salgsordrer. Medarbejdere, der ikke har taget salgsordrer, skal ikke inkluderes i resultaterne. Hvilken type join er påkrævet?

   - [ ] INNER
   - [ ] LEFT OUTER
   - [ ] FULL OUTER

2. Hvilken type JOIN-operation kræver ikke en ON-klausul?

   - [ ] LEFT OUTER JOIN
   - [ ] CROSS JOIN
   - [ ] FULL JOIN

3. Du skriver følgende forespørgsel: 

    ```SQL
    SELECT p.Name, c.Name 
    FROM Store.Product AS p 
    CROSS JOIN Store.Category AS c;
    ``` 

   Hvad returnerer forespørgslen?

   - [ ] Kun datarækker, hvor produktnavnet er det samme som kategorinavnet
   - [ ] Kun rækker, hvor produktnavnet ikke er det samme som kategorinavnet
   - [ ] Hver kombination af produkt- og kategorinavn

---
__SPOILER ALERT__

## Løsninger til Vidensprøve

1. Du skal returnere en liste ....?

   - [x] INNER
   - [ ] LEFT OUTER
   - [ ] FULL OUTER

2. Hvilken type JOIN-operation kræver ...?

   - [ ] LEFT OUTER JOIN
   - [x] CROSS JOIN
   - [ ] FULL JOIN

3. Du skriver følgende forespørgsel:
    ```SQL
    SELECT ...;
    ```
   Hvad returnerer forespørgslen?

   - [ ] Kun datarækker, hvor produktnavnet er det samme som kategorinavnet
   - [ ] Kun rækker, hvor produktnavnet ikke er det samme som kategorinavnet
   - [x] Hver kombination af produkt- og kategorinavn
