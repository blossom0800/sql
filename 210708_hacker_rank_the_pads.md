[the-pads-English.pdf](https://github.com/blossom0800/sql_study/files/6781629/the-pads-English.pdf) <br>
(Source: https://www.hackerrank.com/challenges/the-pads/problem)

`SELECT Name || '(' || SUBSTR(Occupation, 1, 1) || ')'
FROM OCCUPATIONS
ORDER BY Name;`

`SELECT 'There are a total of ' || Count(Occupation) || ' ' || LOWER(Occupation) || 's.'
FROM Occupations
GROUP BY Occupation
ORDER BY Count(Name), Occupation;`

# TIL
 - 그냥 연속해서 쿼리를 입력해도 같이 실행되는구나..There are a total of~ 문장을 계속 첫 번째 select문에 붙일 생각만 했음
 - 두 번째 쿼리문에서 Count(Occupation)은 Count(Name)으로 바꿔도 잘 돌아감
 - 그럼에도 답안 중 첫줄부터 Count(Name)을 쓰는 사람도 있었음. 아마 ORDER BY 절이랑 맞춰주기 위함인듯.
