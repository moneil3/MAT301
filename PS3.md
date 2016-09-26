## Problem Set 3 

1. Define the terms: relation, tuple, attribute, record, and field.

`Relation-table`

***`tuple-row`***

`attribute-column`

`record-row`

`field- intersection of a column and row`

2. What are keys in a relation?

`attributes in a relation that identify a record`

3. What is a surrogate key and how is it used?

`A surrogate key assigns an arbitrary number to a row and has no actual relation to the data. It can be used to replace sensitive information such as social security numbers`

4. In the following equation, Area = Length x Width, identify the determinant(s).

`length and width`

5. If a relation has no duplicate data, how can you be sure there is always at least one primary key?

`...`

6. Give an example of a relation.  Determine a natural key for this relation.

`...`

  For question 7 - 8, Consider product *orders*.  In particular, associated with an order is: customer name (first and last), address (street, city, state, zip), phone, email, the products orders (including item, quantity, and price).  

7. Create a relational data model for *orders*.  Consider applying normalization rules (discuss Monday)

8. For customer, could email be used as a primary key?  If so, state why.  Also, if possible to use as a primary key, discuss any disadvantages of using email as a primary key.

9. Given two relations S and R below find the Cartsian Product S x R. 
10. Find the natural join between the Faculty and Department relations below.

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
