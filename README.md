#  SORTING A TABLE;

USE deff;

SELECT *
FROM employees;

SELECT *
FROM salary;

# TO SORT A TABLE IN ASCENDING AND DESCENDING ORDERS;
SELECT *
FROM employees
ORDER BY first_name ASC;

SELECT *
FROM employees
ORDER BY first_name DESC;

SELECT *
FROM employees
ORDER BY last_name ASC;

SELECT *
FROM employees
ORDER BY last_name DESC;

SELECT *
FROM salary
ORDER BY amount ASC;

SELECT *
FROM salary
ORDER BY amount DESC;
