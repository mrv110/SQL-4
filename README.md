# SQL-Ödev4

1- Film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
```
SELECT COUNT(DISTINCT replacement_cost)
FROM film;
```

2- Film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?
```
SELECT COUNT(title)
FROM film
WHERE title LIKE 'T%' AND rating = 'G';
```

3- Country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
```
SELECT COUNT(country)
FROM country
WHERE country LIKE '_____';
```

4- City tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?
```
SELECT COUNT(city)
FROM city
WHERE city ILIKE '%r';
```
