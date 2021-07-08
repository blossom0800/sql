[the-pads-English.pdf](https://github.com/blossom0800/sql_study/files/6781629/the-pads-English.pdf)
(Source: https://www.hackerrank.com/challenges/the-pads/problem)

`SELECT Name || '(' || SUBSTR(Occupation, 1, 1) || ')'
FROM OCCUPATIONS
ORDER BY Name;

SELECT 'There are a total of ' || Count(Name) || ' ' || LOWER(Occupation) || 's.'
FROM Occupations
GROUP BY Occupation
ORDER BY Count(Name), Occupation;`

# TIL
