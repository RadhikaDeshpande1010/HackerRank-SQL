###
**[HackerRank SQL Query](https://www.hackerrank.com/challenges/select-by-id/problem?isFullScreen=true)**

Problem: Query all columns (attributes) for every row in the CITY table.

Input Format:

The CITY table is described as follows:

|  Field | Type |
|-------|-----|
| ID  | NUMBER |
| NAME | VARCHAR2(17)   |
| COUNTRYCODE  | VARCHAR2(3)  |
| DISTRICT |  VARCHAR2(20) |
| POPULATION | NUMBER |

**Solution**
```sql
SELECT *
FROM CITY
WHERE ID = 1661;
```