# SQL Tasks Examples - Basics

## Write a statement that will select the City column from the Customers table.
```
SELECT City FROM Customers;
```

## Select all the different values from the Country column in the Customers table.

```
SELECT DISTINCT Country FROM Customers;
```

## Select all records where where City is NOT "Berlin".

```SELECT * FROM Customers
WHERE NOT City = `Berlin`;
```

## Select all records from Customers table where the CustomerID column has the value 32.

```
SELECT * FROM Customers
WHERE CustomerID = 32;
```

## Select all records from Customers table where the City column has the value 'Berlin' and the PostalCode column has the value 12209.

```
SELECT * FROM Customers
WHERE City = 'Berlin' 
AND PostalCode = 12209;
```

## Select all records from Customers table where the City column has the value 'Berlin' or 'London'.

```
SELECT * FROM Customers
WHERE City = 'Berlin'
OR City = 'London';
```
## Select all records from the Customers table, sort the result alphabetically, first by the column Country, then, by the column City.

```
SELECT * FROM Customers
ORDER BY Country, City;
```

## Select all records from the Customers table, sort the result reversed alphabetically by the column City.

```
SELECT * FROM Customers
ORDER BY City DESC;
```

## Insert a new record in the Customers table.

### First we need to check what are the components of Customers table.
```
SELECT * FROM Customers;
```
### Results:
![tab](https://github.com/ArkadiuszWrobel/Portfolio/assets/151845080/0d95f39b-1037-4a37-ae16-3838242c4ef5)
### Then we create new record using data above.
```
INSERT INTO Customers (
    CustomerName,
    ContactName,
    Adress,
    City,
    PostalCode,
    Country)
    VALUES (
        `David Tester La Ventura`,
        `David Tester`,
        `Mataderos 12`,
        `Barcelona`,
        `41101`,
        `Spain`
    );
```

## In the Customers T able set the value of the City columns to 'Oslo', but only the ones where the Country column has the value "Norway".

```
UPDATE Customers
SET City = `Oslo`
WHERE Country = `Norway`;
```
