## Problem Set 3 

1. Define the terms: relation, tuple, attribute, record, and field.

***`Relation-table`***


__C__



***`tuple-row`***


__C__



***`attribute-column`***


__C__





***`record-row`***


__C__





***`field- intersection of a column and row`***



__X__ Field is the same as a column (or attribute).  A __CELL__ is the intersection of row/column

2. What are keys in a relation?

***`attributes in a relation that identify a record`***

__C__



3. What is a surrogate key and how is it used?

***`A surrogate key assigns an arbitrary number to a row and has no actual relation to the data. It can be used to replace sensitive information such as social security numbers`***


__C__



4. In the following equation, Area = Length x Width, identify the determinant(s).

***`length and width`***


__C__





5. If a relation has no duplicate data, how can you be sure there is always at least one primary key?

***`The combination of all attributes can provide at least one unique row`***



__C__



6. Give an example of a relation.  Determine a natural key for this relation.

***`An Example of a relation would be alumni of UNE and their attendence at alumni events since graduation. A natural key for this relation would be their student ID number`***



__C__



  For question 7 - 8, Consider product *orders*.  In particular, associated with an order is: customer name (first and last), address (street, city, state, zip), phone, email, the products orders (including item, quantity, and price).  

7. Create a relational data model for *orders*.  Consider applying normalization rules (discuss Monday)

Orders
---------------------------------------------------------------------------------------------------------------
| Order # | first name | Last name | Street Address | Zip Code | Phone | Email | Product_id | Quantity | Price |
|---------|------------|-----------|----------------|----------|-------|-------|------------|----------|-------|

Zip Code
---------------------------
| Zip Code | City | State |
|----------|------|-------|


__I'd break out customer in another table AND there needs to be an ORDERITEMS table.  Note that each order could only have one product in the current model.__



8. For customer, could email be used as a primary key?  If so, state why.  Also, if possible to use as a primary key, discuss any disadvantages of using email as a primary key.

***`Emails could be used as a primary key but it is not practical due to some email addresses being null or no longer in use.`***


__C.  But No email is NULL, wouldn't be an email then__  



9. Given two relations S and R below find the Cartsian Product S x R. 

Cartisian Product
------------------
| R | R | S | S |
|---|---|---|---|
| A | 1 | C | 3 |
| A | 1 | C | 2 |
| A | 1 | C | 2 |
| A | 1 | D | 1 |
| A | 1 | D | 2 |
| A | 1 | D | 1 |
| A | 1 | E | 1 |
| A | 1 | E | 3 |
| A | 1 | E | 5 |
| A | 2 | C | 3 |
| A | 2 | C | 2 |
| A | 2 | C | 2 |
| A | 2 | D | 1 |
| A | 2 | D | 2 |
| A | 2 | D | 1 |
| A | 2 | E | 1 |
| A | 2 | E | 3 |
| A | 2 | E | 5 |
| B | 2 | C | 3 |
| B | 2 | C | 2 |
| B | 2 | C | 2 |
| B | 2 | D | 1 |
| B | 2 | D | 2 |
| B | 2 | D | 1 |
| B | 2 | E | 1 |
| B | 2 | E | 3 |
| B | 2 | E | 5 |
| B | 3 | C | 3 |
| B | 3 | C | 2 |
| B | 3 | C | 2 |
| B | 3 | D | 1 |
| B | 3 | D | 2 |
| B | 3 | D | 1 |
| B | 3 | E | 1 |
| B | 3 | E | 3 |
| B | 3 | E | 5 |
-----------------



__C__




10. Find the natural join between the Faculty and Department relations below.

***`Department`***


__X__


S
--------------
| A | B |
|---|---|
| 1 | 2 |
| 2 | 3 |
---------

R
------------
| C | D | E |
|---|---|---|
| 3 | 1 | 1 |
| 2 | 2 | 3 |
| 2 | 1 | 5 |



Faculty
--------------
| Name | ID | Dept |
|-------|----|----------------|
| Joe | 1 | Chemistry |
| Susan | 2 | Math |
| Tom | 3 | Marine Science |
| Mike | 4 | Math |


Department
------------
| Dept | Chair  |
|---|---|
| Chemistry | John |
| Math | Mike |
| Marine Science | Barry |
