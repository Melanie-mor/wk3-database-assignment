-- 1. Create a database named school
-- CREATE DATABASE school;
-- USE school;
-- 2. Create a table named STUDENT with the following columns:
CREATE TABLE STUDENT(
id INT PRIMARY KEY AUTO_INCREMENT,
fullname VARCHAR(100),
age INT
);
-- 3. Insert the following records into the STUDENT table:
INSERT INTO STUDENT(fullname, age) VALUES
('Ronnie', 24),
('Melanie', 21),
('Sandra', 22);
-- 4. UPDATE records from the STUDENT table
UPDATE STUDENT
SET age=20
WHERE id=2;
