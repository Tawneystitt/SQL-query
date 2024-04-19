<h1></h1>

<h2>Description</h2>
This is a assignment I completed in CIS 310. 
. Queries used must contain 10+ of checklist elements (found on the last page). Check off the elements as you go. (Note, if you create a single question that uses 10 elements, great, that fulfills the ask here)

SELECT PROPERTY_ID, ADDRESS, SQR_FT, MONTHLY_RENT, FLOORS, OWNER_NUM
FROM PROPERTY
WHERE SQR_FT > 1200
AND (BDRMS = 2 OR BDRMS =3)
AND MONTHLY_RENT BETWEEN 1200 and 1700
AND FLOORS is NOT NULL
ORDER BY SQR_FT ASC;

1.	☒SELECT
2.	☒FROM
3.	☒WHERE
4.	☒ORDER BY
5.	☒AND
6.	☒BETWEEN
7.	☒IS NULL/IS NOT NULL
8.	☒OR
9.	☒Comparison Operators < > =!
10.	☒ASC/DESC\


<br />


<h2>Used to create:</h2>

- <b>Sql Server</b> 

<img src="https://i.imgur.com/JoxTQ2n.png" height="80%" width="80%" alt="]"/>
