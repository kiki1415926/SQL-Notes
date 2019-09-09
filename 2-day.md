# 2 day

where:

```text
SELECT * FROM Customers
WHERE Country='Mexico';
```

![](.gitbook/assets/image%20%281%29.png)

![](.gitbook/assets/image%20%2815%29.png)

```text
SELECT * FROM Customers
WHERE City IN ('Paris','London');
```

![](.gitbook/assets/image%20%288%29.png)

```text
SELECT * FROM Customers
WHERE City LIKE 's%';
# s开头
```

![](.gitbook/assets/image%20%283%29.png)

```text
SELECT * FROM Customers
WHERE NOT Country='Germany' AND NOT Country='USA';
```

```text
SELECT * FROM Customers
ORDER BY Country ASC, CustomerName DESC;
```

![](.gitbook/assets/image%20%282%29.png)

INSERT INTO:

原来的表格：

![](.gitbook/assets/image%20%289%29.png)

```text
INSERT INTO Customers (CustomerName, City, Country)
VALUES ('Cardinal', 'Stavanger', 'Norway');
```

![](.gitbook/assets/image%20%2811%29.png)

```text
SELECT CustomerName, ContactName, Address
FROM Customers
WHERE Address IS NOT NULL;
or
WHERE Address IS NULL;
```

SQL UPDATE:

```text
UPDATE Customers
SET ContactName='Juan'
WHERE Country='Mexico';
```

![](.gitbook/assets/image%20%286%29.png)

DELETE FROM

![](.gitbook/assets/image%20%2814%29.png)

```text
DELETE FROM Customers WHERE CustomerName='Alfreds Futterkiste';
```

![](.gitbook/assets/image%20%2813%29.png)



