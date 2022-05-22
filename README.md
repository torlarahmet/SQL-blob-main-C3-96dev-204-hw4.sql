# SQL-blob-main-C3-96dev-204-hw4.sql

SELECT DISTINCT replacement_cost FROM film;

SELECT COUNT (DISTINCT replacement_cost) FROM film;

SELECT COUNT (title LIKE 'T%') FROM film;

SELECT COUNT (country LIKE '_____') FROM country;

SELECT COUNT (city ILIKE '%R') FROM city;
